##### § 79.101 Closed caption decoder requirements for analog television receivers. #####

(a)(1) Effective July 1, 1993, all television broadcast receivers with picture screens 33 cm (13 in) or larger in diameter shipped in interstate commerce, manufactured, assembled, or imported from any foreign country into the United States shall comply with the provisions of this section.

Note to paragraph (a)(1):

This paragraph places no restriction on the shipping or sale of television receivers that were manufactured before July 1, 1993.

(2) Effective January 1, 2014, all television broadcast receivers shipped in interstate commerce, manufactured, assembled, or imported from any foreign country into the United States shall comply with the provisions of this section, if technically feasible, except that television broadcast receivers that use a picture screen less than 13 inches in size must comply with the provisions of this section only if doing so is achievable pursuant to § 79.103(b)(3).

Note to paragraph (a)(2):

This paragraph places no restrictions on the importing, shipping, or sale of television receivers that were manufactured before January 1, 2014.

(b) *Transmission format.* Closed-caption information is transmitted on line 21 of field 1 of the vertical blanking interval of television signals, in accordance with § 73.682(a)(22) of this chapter.

(c) *Operating modes.* The television receiver will employ customer-selectable modes of operation for TV and Caption. A third mode of operation, Text, may be included on an optional basis. The Caption and Text Modes may contain data in either of two operating channels, referred to in this document as C1 and C2. The television receiver must decode both C1 and C2 captioning, and must display the captioning for whichever channel the user selects. The TV Mode of operation allows the video to be viewed in its original form. The Caption and Text Modes define one or more areas (called “boxes”) on the screen within which caption or text characters are displayed.

Note:

For more information regarding Text mode, see “Television Captioning for the Deaf: Signal and Display Specifications”, Engineering Report No. E-7709-C, Public Broadcasting Service, dated May 1980, and “TeleCaption II Decoder Module Performance Specification”, National Captioning Institute, Inc., dated November 1985. These documents are available, respectively, from the Public Broadcasting Service, 1320 Braddock Place, Alexandria, VA 22314 and from the National Captioning Institute, Inc., 5203 Leesburg Pike, Falls Church, VA 22041.

(d) *Screen format.* The display area for captioning and text shall fall approximately within the safe caption area as defined in paragraph (n)(12) of this section. This display area will be further divided into 15 character rows of equal height and 32 columns of equal width, to provide accurate placement of text on the screen. Vertically, the display area begins on line 43 and is 195 lines high, ending on line 237 on an interlaced display. All captioning and text shall fall within these established columns and rows. The characters must be displayed clearly separated from the video over which they are placed. In addition, the user must have the capability to select a black background over which the captioned letters are displaced.

(1) *Caption mode.* In the Caption Mode, text can appear on up to 4 rows simultaneously anywhere on the screen within the defined display area. In addition, a solid space equal to one column width may be placed before the first character and after the last character of each row to enhance legibility. The caption area will be transparent anywhere that either:

(i) No standard space character or other character has been addressed and no accompanying solid space is needed; or,

(ii) An accompanying solid space is used and a “transparent space” special character has been addressed which does not immediately precede or follow a displayed character.

(2) [Reserved]

(e) *Presentation format.* In analyzing the presentation of characters, it is convenient to think in terms of a non-visible cursor which marks the screen position at which the next event in a given mode and data channel will occur. The receiver remembers the cursor position for each mode even when data are received for a different address in an alternate mode or data channel.

(1) *Screen addressing.* Two kinds of control codes are used to move the cursor to specific screen locations. In Caption Mode, these addressing codes will affect both row and column positioning. In Text Mode, the codes affect only column positioning. In both modes, the addressing codes are optional. Default positions are defined for each mode and style when no addressing code is provided.

(i) The first type of addressing code is the Preamble Address Code (PAC). It assigns a row number and one of eight “indent” figures. Each successive indent moves the cursor four columns to the right (starting from the left margin). Thus, an indent of 0 places the cursor at Column 1, an indent of 4 sets it at Column 5, etc. The PAC indent is non-destructive to displayable characters. It will not affect the display to the left of the new cursor position on the indicated row. Note that Preamble Address Codes also set initial attributes for the displayable characters which follow. See paragraph (h) of this section and the Preamble Address Code table.

(ii) The second type of addressing code is the Tab Offset, which is one of three Miscellaneous Control Codes. Tab Offset will move the cursor one, two, or three columns to the right. The character cells skipped over will be unaffected; displayable characters in these cells, if any, will remain intact while empty cells will remain empty, in the same manner that a PAC indent is non-destructive.

(2) [Reserved]

(f) *Caption Mode.* There are three styles of presenting text in Caption Mode: roll-up, pop-on, and paint-on. Character display varies significantly with the style used, but certain rules of character erasure are common to all styles. A character can be erased by addressing another character to the same screen location or by backspacing over the character from a subsequent location on the same row. The entire displayed memory will be erased instantly by receipt of an Erase Displayed Memory command. Both displayed memory and non-displayed memory will be entirely erased simultaneously by either: The user switching receiver channels or data channels (C1/C2) or fields (F1/F2) in decoders so equipped; the loss of valid data (see paragraph (j) of this section); or selecting non-captioning receiver functions which use the display memory of the decoder. Receipt of an End of Caption command will cause a displayed caption to become non-displayed (and vice versa) without being erased from memory. Changing the receiver to a non-captioning mode which does not require use of the decoder's display memory will leave that memory intact, and the decoder will continue to process data as if the caption display were selected.

(1) *Roll-up.* Roll-up style captioning is initiated by receipt of one of three Miscellaneous Control Codes that determine the maximum number of rows displayed simultaneously, either 2, 3 or 4 contiguous rows. These are the three Roll-Up Caption commands.

(i) The bottom row of the display is known as the “base row”. The cursor always remains on the base row. Rows of text roll upwards into the contiguous rows immediately above the base row to create a “window” 2 to 4 rows high.

(ii) The Roll-Up command, in normal practice, will be followed (not necessarily immediately) by a Preamble Address Code indicating the base row and the horizontal indent position. If no Preamble Address Code is received, the base row will default to Row 15 or, if a roll-up caption is currently displayed, to the same base row last received, and the cursor will be placed at Column 1. If the Preamble Address Code received contains a different base row than that of a currently displayed caption, the entire window will move intact (and without erasing) to the new base row immediately.

(iii) Each time a Carriage Return is received, the text in the top row of the window is erased from memory and from the display or scrolled off the top of the window. The remaining rows of text are each rolled up into the next highest row in the window, leaving the base row blank and ready to accept new text. This roll-up must appear smooth to the user, and must take no more than 0.433 second to complete. The cursor is automatically placed at Column 1 (pending receipt of a Preamble Address Code).

(iv) Increasing or decreasing the number of roll-up rows instantly changes the size of the active display window, appropriately turning on or off the display of the top one or two rows. A row which is turned off should also be erased from memory.

(v) Characters are always displayed immediately when received by the receiver. Once the cursor reaches the 32nd column position on any row, all subsequent characters received prior to a Carriage Return, Preamble Address Code, or Backspace will be displayed in that column replacing any previous character occupying that address.

(vi) The cursor moves automatically one column to the right after each character or Mid-Row Code received. A Backspace will move the cursor one column to the left, erasing the character or Mid-Row Code occupying that location. (A Backspace received when the cursor is in Column 1 will be ignored.)

(vii) The Delete to End of Row command will erase from memory any characters or control codes starting at the current cursor location and in all columns to its right on the same row. If no displayable characters remain on the row after the Delete to End of Row is acted upon, the solid space (if any) for that row should also be erased to conform with the following provisions.

(viii) If a solid space is used for legibility, it should appear when the first displayable character (not a transparent space) or Mid-Row Code is received on a row, not when the Preamble Address Code, if any, is given. A row on which there are no displayable characters or Mid-Row Codes will not display a solid space, even when rolled up between two rows which do display a solid space.

(ix) If the reception of data for a row is interrupted by data for the alternate data channel or for Text Mode, the display of caption text will resume from the same cursor position if a Roll-Up Caption command is received and no Preamble Address Code is given which would move the cursor.

(x) A roll-up caption remains displayed until one of the standard caption erasure techniques is applied. Receipt of a Resume Caption Loading command (for pop-on style) or a Resume Direct Captioning command (for paint-on style) will not affect a roll-up display. Receipt of a Roll-Up Caption command will cause any pop-on or paint-on caption to be erased from displayed memory and non-displayed memory.

(2) *Pop-on.* Pop-on style captioning is initiated by receipt of a Resume Caption Loading command. Subsequent data are loaded into a non-displayed memory and held there until an End of Caption command is received, at which point the non-displayed memory becomes the displayed memory and vice versa. (This process is often referred to as “flipping memories” and does not automatically erase memory.) An End of Caption command forces the receiver into pop-on style if no Resume Caption Loading command has been received which would do so. The display will be capable of 4 full rows, not necessarily contiguous, simultaneous anywhere on the screen.

(i) Preamble Address Codes can be used to move the cursor around the screen in random order to place captions on Rows 1 to 15. Carriage Returns have no effect on cursor location during caption loading.

(ii) The cursor moves automatically one column to the right after each character or Mid-Row Code received. Receipt of a Backspace will move the cursor one column to the left, erasing the character or Mid-Row Code occupying that location. (A Backspace received when the cursor is in Column 1 will be ignored.) Once the cursor reaches the 32nd column position on any row, all subsequent characters received prior to a Backspace, an End of Caption, or a Preamble Address Code, will replace any previous character at that location.

(iii) The Delete to End of Row command will erase from memory any characters or control codes starting at the current cursor location and in all columns to its right on the same row. If no displayable characters remain on a row after the Delete to End of Row is acted upon, the solid space (if any) for that element should also be erased.

(iv) If data reception is interrupted during caption loading by data for the alternate caption channel or for Text Mode, caption loading will resume at the same cursor position if a Resume Caption Loading command is received and no Preamble Address Code is given that would move the cursor.

(v) Characters remain in non-displayed memory until an End of Caption command flips memories. The caption will be erased without being displayed upon receipt of an Erase Non-Displayed Memory command, a Roll-Up Caption command, or if the user switches receiver channels, data channels or fields, or upon the loss of valid data (see paragraph (j) of this section).

(vi) A pop-on caption, once displayed, remains displayed until one of the standard caption erasure techniques is applied or until a Roll-Up Caption command is received. Characters within a displayed pop-on caption will be replaced by receipt of the Resume Direct Captioning command and paint-on style techniques (see below).

(3) *Paint-on.* Paint-on style captioning is initiated by receipt of a Resume Direct Captioning command. Subsequent data are addressed immediately to displayed memory without need for an End of Caption command.

(i) Preamble Address Codes can be used to move the cursor around the screen in random order to display captions on Rows 1 to 15. Carriage Returns have no affect on cursor location during direct captioning. The cursor moves automatically one column to the right after each character or Mid-Row Code is received. Receipt of a Backspace will move the cursor one column to the left, erasing the character or Mid-Row Code occupying that location. (A Backspace received when the cursor is in Column 1 will be ignored.) Once the cursor reaches the 32nd column position on any row, all subsequent characters received prior to a Preamble Address Code or Backspace will be displayed in that column replacing any previous character occupying that location.

(ii) The Delete to End of Row command will erase from memory any characters or control codes starting at the current cursor location and in all columns to its right on the same row. If no displayable characters remain on the row after the Delete to End of Row is acted upon, the solid space (if any) for that element should also be erased.

(iii) If the reception of data is interrupted during the direct captioning by data for the alternate caption channel or for Text Mode, the display of caption text will resume at the same cursor position if a Resume Direct Captioning command is received and no Preamble Address Code is given which would move the cursor.

(iv) Characters remain displayed until one of the standard caption erasure techniques is applied or until a Roll-Up Caption command is received. An End of Caption command leaves a paint-on caption fully intact in non-displayed memory. In other words, a paint-on style caption behaves precisely like a pop-on style caption which has been displayed.

(g) *Character format.* Characters are to be displayed on the screen within a character “cell” which is the height and width of a single row and column. The following codes define the displayable character set. Television receivers manufactured prior to January 1, 1996 and having a character resolution of 5 × 7 dots, or less, may display the allowable alternate characters in the character table. A statement must be in a prominent location on the box or other package in which the receiver is to be marketed, and information must be in the owner's manual, indicating the receiver displays closed captioning in upper case only.

Character Set TableSpecial Characters

These require two bytes for each symbol. Each hex code as shown will be preceded by a 11h for data channel 1 or by a 19h for data channel 2. For example: 19h 37h will place a musical note in data channel 2.

|                                                                                                                                                                                                                                                HEX                                                                                                                                                                                                                                                 |         Example         |      Alternate      |         Description          |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|------------------------------|
|                                                                                                                                                                                                                                                 30                                                                                                                                                                                                                                                 |            ®            |See note <sup>1</sup>|    Registered mark symbol    |
|                                                                                                                                                                                                                                                 31                                                                                                                                                                                                                                                 |            °            |                     |         Degree sign          |
|                                                                                                                                                                                                                                                 32                                                                                                                                                                                                                                                 |<sup>1</sup>⁄<sub>2</sub>|                     |  <sup>1</sup>⁄<sub>2</sub>   |
|                                                                                                                                                                                                                                                 33                                                                                                                                                                                                                                                 |            ¿            |                     |        Inverse query         |
|                                                                                                                                                                                                                                                 34                                                                                                                                                                                                                                                 |      <sup>TM</sup>      |See note <sup>1</sup>|       Trademark symbol       |
|                                                                                                                                                                                                                                                 35                                                                                                                                                                                                                                                 |            ¢            |                     |          Cents sign          |
|                                                                                                                                                                                                                                                 36                                                                                                                                                                                                                                                 |            £            |                     |     Pounds Sterling sign     |
|                                                                                                                                                                                                                                                 37                                                                                                                                                                                                                                                 |            ♪            |                     |          Music note          |
|                                                                                                                                                                                                                                                 38                                                                                                                                                                                                                                                 |            à            |          A          |Lower-case a with grave accent|
|                                                                                                                                                                                                                                                 39                                                                                                                                                                                                                                                 |                         |                     |      Transparent space       |
|                                                                                                                                                                                                                                                 3A                                                                                                                                                                                                                                                 |            è            |          E          |Lower-case e with grave accent|
|                                                                                                                                                                                                                                                 3B                                                                                                                                                                                                                                                 |            â            |          A          | Lower-case a with circumflex |
|                                                                                                                                                                                                                                                 3C                                                                                                                                                                                                                                                 |            ê            |          E          | Lower-case e with circumflex |
|                                                                                                                                                                                                                                                 3D                                                                                                                                                                                                                                                 |            î            |          I          | Lower-case i with circumflex |
|                                                                                                                                                                                                                                                 3E                                                                                                                                                                                                                                                 |            ô            |          O          | Lower-case o with circumflex |
|                                                                                                                                                                                                                                                 3F                                                                                                                                                                                                                                                 |            û            |          U          | Lower-case u with circumflex |
|<sup>1</sup>**Note:** The registered and trademark symbols are used to satisfy certain legal requirements. There are various legal ways in which these symbols may be drawn or displayed. For example, the trademark symbol may be drawn with the “T” next to the “M” or over the “M”. It is preferred that the trademark symbol be superscripted, i.e., XYZ <sup>TM</sup>. It is left to each individual manufacturer to interpret these symbols in any way that meets the legal needs of the user.|                         |                     |                              |

Standard characters

|HEX|Example|Alternate|         Description          |
|---|-------|---------|------------------------------|
|20 |       |         |        Standard space        |
|21 |   !   |         |       Exclamation mark       |
|22 |   “   |         |        Quotation mark        |
|23 |  \#   |         |     Pounds (number) sign     |
|24 |   $   |         |         Dollar sign          |
|25 |   %   |         |       Percentage sign        |
|26 |   &   |         |          Ampersand           |
|27 |   '   |         |          Apostrophe          |
|28 |   (   |         |       Open parentheses       |
|29 |   )   |         |      Close parentheses       |
|2A |   á   |    A    |Lower-case a with acute accent|
|2B |  \+   |         |          Plus sign           |
|2C |   ,   |         |            Comma             |
|2D |   −   |         |     Minus (hyphen) sign      |
|2E |   .   |         |            Period            |
|2F |   /   |         |            Slash             |
|30 |   0   |         |             Zero             |
|31 |   1   |         |             One              |
|32 |   2   |         |             Two              |
|33 |   3   |         |            Three             |
|34 |   4   |         |             Four             |
|35 |   5   |         |             Five             |
|36 |   6   |         |             Six              |
|37 |   7   |         |            Seven             |
|38 |   8   |         |            Eight             |
|39 |   9   |         |             Nine             |
|3A |   :   |         |            Colon             |
|3B |   ;   |         |          Semi-colon          |
|3C |  \<   |         |        Less than sign        |
|3D |  \=   |         |          Equal sign          |
|3E |  \>   |         |      Greater than sign       |
|3F |   ?   |         |        Question mark         |
|40 |   @   |         |           At sign            |
|41 |   A   |         |         Upper-case A         |
|42 |   B   |         |         Upper-case B         |
|43 |   C   |         |         Upper-case C         |
|44 |   D   |         |         Upper-case D         |
|45 |   E   |         |         Upper-case E         |
|46 |   F   |         |         Upper-case F         |
|47 |   G   |         |         Upper-case G         |
|48 |   H   |         |         Upper-case H         |
|49 |   I   |         |         Upper-case I         |
|4A |   J   |         |         Upper-case J         |
|4B |   K   |         |         Upper-case K         |
|4C |   L   |         |         Upper-case L         |
|4D |   M   |         |         Upper-case M         |
|4E |   N   |         |         Upper-case N         |
|4F |   O   |         |         Upper-case O         |
|50 |   P   |         |         Upper-case P         |
|51 |   Q   |         |         Upper-case Q         |
|52 |   R   |         |         Upper-case R         |
|53 |   S   |         |         Upper-case S         |
|54 |   T   |         |         Upper-case T         |
|55 |   U   |         |         Upper-case U         |
|56 |   V   |         |         Upper-case V         |
|57 |   W   |         |         Upper-case W         |
|58 |   X   |         |         Upper-case X         |
|59 |   Y   |         |         Upper-case Y         |
|5A |   Z   |         |         Upper-case Z         |
|5B |   [   |         |         Open bracket         |
|5C |   é   |    E    |Lower-case e with acute accent|
|5D |   ]   |         |        Close bracket         |
|5E |   í   |    I    |Lower-case i with acute accent|
|5F |   ó   |    O    |Lower-case o with acute accent|
|60 |   ú   |    U    |Lower-case u with acute accent|
|61 |   a   |    A    |         Lower-case a         |
|62 |   b   |    B    |         Lower-case b         |
|63 |   c   |    C    |         Lower-case c         |
|64 |   d   |    D    |         Lower-case d         |
|65 |   e   |    E    |         Lower-case e         |
|66 |   f   |    F    |         Lower-case f         |
|67 |   g   |    G    |         Lower-case g         |
|68 |   h   |    H    |         Lower-case h         |
|69 |   i   |    I    |         Lower-case i         |
|6A |   j   |    J    |         Lower-case j         |
|6B |   k   |    K    |         Lower-case k         |
|6C |   l   |    L    |         Lower-case l         |
|6D |   m   |    M    |         Lower-case m         |
|6E |   n   |    N    |         Lower-case n         |
|6F |   o   |    O    |         Lower-case o         |
|70 |   p   |    P    |         Lower-case p         |
|71 |   q   |    Q    |         Lower-case q         |
|72 |   r   |    R    |         Lower-case r         |
|73 |   s   |    S    |         Lower-case s         |
|74 |   t   |    T    |         Lower-case t         |
|75 |   u   |    U    |         Lower-case u         |
|76 |   v   |    V    |         Lower-case v         |
|77 |   w   |    W    |         Lower-case w         |
|78 |   x   |    X    |         Lower-case x         |
|79 |   y   |    Y    |         Lower-case y         |
|7A |   z   |    Z    |         Lower-case z         |
|7B |   ç   |    C    |  Lower-case c with cedilla   |
|7C |   ÷   |         |        Division sign         |
|7D |   Ñ   |         |   Upper-case N with tilde    |
|7E |   ñ   |    Ñ    |   Lower-case n with tilde    |
|7F |   ▪   |         |         Solid block          |

(h) *Character Attributes*—(1) *Transmission of Attributes.* A character may be transmitted with any or all of four attributes: Color, italics, underline, and flash. All of these attributes are set by control codes included in the received data. An attribute will remain in effect until changed by another control code or until the end of the row is reached. Each row begins with a control code which sets the color and underline attributes. (White non-underlined is the default display attribute if no Preamble Address Code is received before the first character on an empty row.) Attributes are not affected by transparent spaces within a row.

(i) All Mid-Row Codes and the Flash On command are spacing attributes which appear in the display just as if a standard space (20h) had been received. Preamble Address Codes are non-spacing and will not alter any attributes when used to position the cursor in the midst of a row of characters.

(ii) The color attribute has the highest priority and can only be changed by the Mid-Row Code of another color. Italics has the next highest priority. If characters with both color and italics are desired, the italics Mid-Row Code must follow the color assignment. Any color Mid-Row Code will turn off italics. If the least significant bit of a Preamble Address Code or of a color or italics Mid-Row Code is a 1 (high), underlining is turned on. If that bit is a 0 (low), underlining is off.

(iii) The flash attribute is transmitted as a Miscellaneous Control Code. The Flash On command will not alter the status of the color, italics, or underline attributes. However, any color or italics Mid-Row Code will turn off flash.

(iv) Thus, for example, if a red, italicized, underlined, flashing character is desired, the attributes must be received in the following order: a red Mid-Row or Preamble Address Code, an italics Mid-Row Code with underline bit, and the Flash On command. The character will then be preceded by three spaces (two if red was assigned via a Preamble Address Code).

(2) *Display of attributes.* The underline attribute will be displayed by drawing a line beneath the character in the same color as the character. The flash attribute will be displayed by causing the character to blink from the display at least once per second. The italic attribute must be capable of being displayed by either a special italic font, or by the modification of the standard font by slanting. The user may be given the option to select other methods of italic display as well. The support of the color attributes is optional. If the color attributes are supported, they will be displayed in the color they have been assigned. If color attributes are not supported, the display may be in color, but all color changes will be ignored.

(i) *Control codes.* There are three different types of control codes used to identify the format, location, attributes, and display of characters: Preamble Address Codes, Mid-Row Codes, and Miscellaneous Control Codes.

(1) Each control code consists of a pair of bytes which are always transmitted together in a single field of line 21 and which are normally transmitted twice in succession to help insure correct reception of the control instructions. The first of the control code bytes is a non-printing character in the range 10h to 1Fh. The second byte is always a printing character in the range 20h to 7Fh. Any such control code pair received which has not been assigned a function is ignored. If the non-printing character in the pair is in the range 00h to 0Fh, that character alone will be ignored and the second character will be treated normally.

(2) If the second byte of a control code pair does not contain odd parity (see paragraph (j) of this section), then the pair is ignored. The redundant transmission of the pair will be the instruction upon which the receiver acts.

(3) If the first byte of the first transmission of a control code pair fails the parity check, then that byte is inserted into the currently active memory as a solid block character (7Fh) followed by whatever the second byte is. Again, the redundant transmission of the pair will be the controlling instruction.

(4) If the first transmission of a control code pair passes parity, it is acted upon within one video frame. If the next frame contains a perfect repeat of the same pair, the redundant code is ignored. If, however, the next frame contains a different but also valid control code pair, this pair, too, will be acted upon (and the receiver will expect a repeat of this second pair in the next frame). If the first byte of the expected redundant control code pair fails the parity check and the second byte is identical to the second byte in the immediately preceding pair, then the expected redundant code is ignored. If there are printing characters in place of the redundant code, they will be processed normally.

(5) There is provision for decoding a second data channel. The second data channel is encoded with the same control codes and procedures already described. The first byte of every control code pair indicates the data channel (C1/C2) to which the command applies. Control codes which do not match the data channel selected by the user, and all subsequent data related to that control code, are ignored by the receiver.

|Data channel 1|Data channel 2|Attribute description|
|--------------|--------------|---------------------|
|    11 20     |    19 20     |       White.        |
|    11 21     |    19 21     |  White Underline.   |
|    11 22     |    19 22     |       Green.        |
|    11 23     |    19 23     |  Green Underline.   |
|    11 24     |    19 24     |        Blue.        |
|    11 25     |    19 25     |   Blue Underline.   |
|    11 26     |    19 26     |        Cyan.        |
|    11 27     |    19 27     |   Cyan Underline.   |
|    11 28     |    19 28     |        Red.         |
|    11 29     |    19 29     |   Red Underline.    |
|    11 2A     |    19 2A     |       Yellow.       |
|    11 2B     |    19 2B     |  Yellow Underline.  |
|    11 2C     |    19 2C     |      Magenta.       |
|    11 2D     |    19 2D     | Magenta Underline.  |
|    11 2E     |    19 2E     |      Italics.       |
|    11 2F     |    19 2F     | Italics Underline.  |

|Data channel 1|Data channel 2|Mne-  <br/>monic|      Command description      |
|--------------|--------------|----------------|-------------------------------|
|    14 20     |    1C 20     |      RCL       |    Resume caption loading.    |
|    14 21     |    1C 21     |       BS       |          Backspace.           |
|    14 22     |    1C 22     |      AOF       |Reserved (formerly Alarm Off). |
|    14 23     |    1C 23     |      AON       | Reserved (formerly Alarm On). |
|    14 24     |    1C 24     |      DER       |     Delete to End of Row.     |
|    14 25     |    1C 25     |      RU2       |   Roll-Up Captions-2 Rows.    |
|    14 26     |    1C 26     |      RU3       |   Roll-Up Captions-3 Rows.    |
|    14 27     |    1C 27     |      RU4       |   Roll-Up Captions-4 Rows.    |
|    14 28     |    1C 28     |      FON       |           Flash On.           |
|    14 29     |    1C 29     |      RDC       |   Resume Direct Captioning.   |
|    14 2A     |    1C 2A     |       TR       |         Text Restart.         |
|    14 2B     |    1C 2B     |      RTD       |     Resume Text Display.      |
|    14 2C     |    1C 2C     |      EDM       |    Erase Displayed Memory.    |
|    14 2D     |    1C 2D     |       CR       |       Carriage Return.        |
|    14 2E     |    1C 2E     |      ENM       |  Erase Non-Displayed Memory.  |
|    14 2F     |    1C 2F     |      EOC       |End of Caption (Flip Memories).|
|    17 21     |    1F 21     |      TO1       |     Tab Offset 1 Column.      |
|    17 22     |    1F 22     |      TO2       |     Tab Offset 2 Columns.     |
|    17 23     |    1F 23     |      TO3       |     Tab Offset 3 Columns.     |

|                                                                                                      |Row 1|Row 2|Row 3|Row 4|Row 5|Row 6|Row 7|Row 8|Row 9|Row 10|Row 11|Row 12|Row 13|Row 14|Row 15|
|------------------------------------------------------------------------------------------------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|------|------|------|------|------|
|                                       First byte of code pair:                                       |     |     |     |     |     |     |     |     |     |      |      |      |      |      |      |
|                                            Data Channel 1                                            | 11  | 11  | 12  | 12  | 15  | 15  | 16  | 16  | 17  |  17  |  10  |  13  |  13  |  14  |  14  |
|                                            Data Channel 2                                            | 19  | 19  | 1A  | 1A  | 1D  | 1D  | 1E  | 1E  | 1F  |  1F  |  18  |  1B  |  1B  |  1C  |  1C  |
|                                      Second byte of code pair:                                       |     |     |     |     |     |     |     |     |     |      |      |      |      |      |      |
|                                                White                                                 | 40  | 60  | 40  | 60  | 40  | 60  | 40  | 60  | 40  |  60  |  40  |  40  |  60  |  40  |  60  |
|                                           White Underline                                            | 41  | 61  | 41  | 61  | 41  | 61  | 41  | 61  | 41  |  61  |  41  |  41  |  61  |  41  |  61  |
|                                                Green                                                 | 42  | 62  | 42  | 62  | 42  | 62  | 42  | 62  | 42  |  62  |  42  |  42  |  62  |  42  |  62  |
|                                           Green Underline                                            | 43  | 63  | 43  | 63  | 43  | 63  | 43  | 63  | 43  |  63  |  43  |  43  |  63  |  43  |  63  |
|                                                 Blue                                                 | 44  | 64  | 44  | 64  | 44  | 64  | 44  | 64  | 44  |  64  |  44  |  44  |  64  |  44  |  64  |
|                                            Blue Underline                                            | 45  | 65  | 45  | 65  | 45  | 65  | 45  | 65  | 45  |  65  |  45  |  45  |  65  |  45  |  65  |
|                                                 Cyan                                                 | 46  | 66  | 46  | 66  | 46  | 66  | 46  | 66  | 46  |  66  |  46  |  46  |  66  |  46  |  66  |
|                                            Cyan Underline                                            | 47  | 67  | 47  | 67  | 47  | 67  | 47  | 67  | 47  |  67  |  47  |  47  |  67  |  47  |  67  |
|                                                 Red                                                  | 48  | 68  | 48  | 68  | 48  | 68  | 48  | 68  | 48  |  68  |  48  |  48  |  68  |  48  |  68  |
|                                            Red Underline                                             | 49  | 69  | 49  | 69  | 49  | 69  | 49  | 69  | 49  |  69  |  49  |  49  |  69  |  49  |  69  |
|                                                Yellow                                                | 4A  | 6A  | 4A  | 6A  | 4A  | 6A  | 4A  | 6A  | 4A  |  6A  |  4A  |  4A  |  6A  |  4A  |  6A  |
|                                           Yellow Underline                                           | 4B  | 6B  | 4B  | 6B  | 4B  | 6B  | 4B  | 6B  | 4B  |  6B  |  4B  |  4B  |  68  |  4B  |  6B  |
|                                               Magenta                                                | 4C  | 6C  | 4C  | 6C  | 4C  | 6C  | 4C  | 6C  | 4C  |  6C  |  4C  |  4C  |  6C  |  4C  |  6C  |
|                                          Magenta Underline                                           | 4D  | 6D  | 4D  | 6D  | 4D  | 6D  | 4D  | 6D  | 4D  |  6D  |  4D  |  4D  |  6D  |  4D  |  6D  |
|                                            White Italics                                             | 4E  | 6E  | 4E  | 6E  | 4E  | 6E  | 4E  | 6E  | 4E  |  6E  |  4E  |  4E  |  6E  |  4E  |  6E  |
|                                       White Italics Underline                                        | 4F  | 6F  | 4F  | 6F  | 4F  | 6F  | 4F  | 6F  | 4F  |  6F  |  4F  |  4F  |  6F  |  4F  |  6F  |
|                                               Indent 0                                               | 50  | 70  | 50  | 70  | 50  | 70  | 50  | 70  | 50  |  70  |  50  |  50  |  70  |  50  |  70  |
|                                          Indent 0 Underline                                          | 51  | 71  | 51  | 71  | 51  | 71  | 51  | 71  | 51  |  71  |  51  |  51  |  71  |  51  |  71  |
|                                               Indent 4                                               | 52  | 72  | 52  | 72  | 52  | 72  | 52  | 72  | 52  |  72  |  52  |  52  |  72  |  52  |  72  |
|                                          Indent 4 Underline                                          | 53  | 73  | 53  | 73  | 53  | 73  | 53  | 73  | 53  |  73  |  53  |  53  |  73  |  53  |  73  |
|                                               Indent 8                                               | 54  | 74  | 54  | 74  | 54  | 74  | 54  | 74  | 54  |  74  |  54  |  54  |  74  |  54  |  74  |
|                                          Indent 8 Underline                                          | 55  | 75  | 55  | 75  | 55  | 75  | 55  | 75  | 55  |  75  |  55  |  55  |  75  |  55  |  75  |
|                                              Indent 12                                               | 56  | 76  | 56  | 76  | 56  | 76  | 56  | 76  | 56  |  76  |  56  |  56  |  76  |  56  |  76  |
|                                         Indent 12 Underline                                          | 57  | 77  | 57  | 77  | 57  | 77  | 57  | 77  | 57  |  77  |  57  |  57  |  77  |  57  |  77  |
|                                              Indent 16                                               | 58  | 78  | 58  | 78  | 58  | 78  | 58  | 78  | 58  |  78  |  58  |  58  |  78  |  58  |  78  |
|                                         Indent 16 Underline                                          | 59  | 79  | 59  | 79  | 59  | 79  | 59  | 79  | 59  |  79  |  59  |  59  |  79  |  59  |  79  |
|                                              Indent 20                                               | 5A  | 7A  | 5A  | 7A  | 5A  | 7A  | 5A  | 7A  | 5A  |  7A  |  5A  |  5A  |  7A  |  5A  |  7A  |
|                                         Indent 20 Underline                                          | 5B  | 7B  | 5B  | 7B  | 5B  | 7B  | 5B  | 7B  | 5B  |  7B  |  5B  |  5B  |  7B  |  5B  |  7B  |
|                                              Indent 24                                               | 5C  | 7C  | 5C  | 7C  | 5C  | 7C  | 5C  | 7C  | 5C  |  7C  |  5C  |  5C  |  7C  |  5C  |  7C  |
|                                         Indent 24 Underline                                          | 5D  | 7D  | 5D  | 7D  | 5D  | 7D  | 5D  | 7D  | 5D  |  7D  |  5D  |  5D  |  7D  |  5D  |  7D  |
|                                              Indent 28                                               | 5E  | 7E  | 5E  | 7E  | 5E  | 7E  | 5E  | 7E  | 5E  |  7E  |  5E  |  5E  |  7E  |  5E  |  7E  |
|                                         Indent 28 Underline                                          | 5F  | 7F  | 5F  | 7F  | 5F  | 7F  | 5F  | 7F  | 5F  |  7F  |  5F  |  5F  |  7F  |  5F  |  7F  |
|**Note:** All indent codes (second byte equals 50h-5fh, 70th-7fh) assign white as the color attribute.|     |     |     |     |     |     |     |     |     |      |      |      |      |      |      |

(j) *Data rejection.* The receiver should provide an effective procedure to verify data. A receiver will reject data if the data is invalid, or if the data is directed to the data channel or field not selected by the user. Invalid data is any data that fails to pass a check for odd parity, or which, having passed the parity check, is assigned no function.

(1) If a print character fails to pass a check for parity, a solid block (7Fh) should be displayed in place of the failed character. In addition, valid data can be corrupted in many ways and may not be suitable for display. For example, repeated fields, skipped fields and altered field sequences are all possible from consumer video equipment and might present meaningless captions.

(2) The receiver will ignore data rejected due to being directed to a deselected field or channel. However, this will not cause the display to be disabled.

(k) *Automatic display enable/disable.* The receiver shall provide an automatic enable/disable capability to prevent the display of invalid or incomplete data, when the user selects the Caption Mode. The display should automatically become enable after the receiver verifies the data as described in paragraph (j) of this section. The display will be automatically disabled when there is a sustained detection of invalid data. The display will be re-enabled when the data verification process has been satisfied once again.

(l) *Compatibility with Cable Security Systems.* Certain cable television security techniques, such as signal encryption and copy protection, can alter the television signal so that some methods of finding line 21 will not work. In particular, counting of lines or timing from the start of the vertical blanking interval may cause problems. Caption decoding circuitry must function properly when receiving signals from cable security systems that were designed and marketed prior to April 5, 1991. Further information concerning such systems is available from the National Cable Television Association, Inc., Washington, DC, and from the Electronic Industries Association, Washington, DC.

(m) [Reserved]

(n) *Glossary of terms.* The following terms are used to describe caption decoder specifications:

(1) *Base row:* The bottom row of a roll-up display. The cursor always remains on the base row. Rows of text roll upwards into the contiguous rows immediately above the base row.

(2) *Box:* The area surrounding the active character display. In Text Mode, the box is the entire screen area defined for display, whether or not displayable characters appear. In Caption Mode, the box is dynamically redefined by each caption and each element of displayable characters within a caption. The box (or boxes, in the case of a multiple-element caption) includes all the cells of the displayed characters, the non-transparent spaces between them, and one cell at the beginning and end of each row within a caption element in those decoders that use a solid space to improve legibility.

(3) *Caption window:* The invisible rectangle which defines the top and bottom limits of a roll-up caption. The window can be 2 to 4 rows high. The lowest row of the window is called the base row.

(4) *Cell:* The discrete screen area in which each displayable character or space may appear. A cell is one row high and one column wide.

(5) *Column:* One of 32 vertical divisions of the screen, each of equal width, extending approximately across the full width of the safe caption area as defined in paragraph (n)(12) of this section. Two additional columns, one at the left of the screen and one at the right, may be defined for the appearance of a box in those decoders which use a solid space to improve legibility, but no displayable characters may appear in those additional columns. For reference, columns may be numbered 0 to 33, with columns 1 to 32 reserved for displayable characters.

(6) *Displayable character:* Any letter, number or symbol which is defined for on-screen display, plus the 20h space.

(7) *Display disable:* To turn off the display of captions or text (and accompanying background) at the receiver, rather than through codes transmitted on line 21 which unconditionally erase the display. The receiver may disable the display because the user selects an alternate mode, e.g., TV Mode, or because no valid line 21 data is present.

(8) *Display enable:* To allow the display of captions or text when they are transmitted on line 21 and received as valid data. For display to be enabled, the user must have selected Caption Mode or Text Mode, and valid data for the selected mode must be present on line 21.

(9) *Element:* In a pop-on or paint-on style caption, each contiguous area of cells containing displayable characters and non-transparent spaces between those characters. A single caption may have multiple elements. An element is not necessarily a perfect rectangle, but may include rows of differing widths.

(10) *Erase Display:* In Caption Mode, to clear the screen of all characters (and accompanying background) in response to codes transmitted on line 21. (The caption service provider can accomplish the erasure either by sending an Erase Displayed Memory command or by sending an Erase Non-Displayed Memory command followed by an End of Caption command, effectively making a blank caption “appear”.) Display can also be erased by the receiver when the caption memory erasure conditions are met, such as the user changing TV channels.

(11) *Row:* One of 15 horizontal divisions of the screen, extending across the full height of the safe caption area as defined in paragraph (n)(12) of this section.

(12) *Safe caption area:* The area of the television picture within which captioning and text shall be displayed to ensure visibility of the information on the majority of home television receivers. The safe caption area is specified as shown in the following figure:

![](/graphics/ec03jn91.009.gif)

The dimensions of the above figure shall be as follows:

|Label|               Dimensions               |Percent of television picture height|
|-----|----------------------------------------|------------------------------------|
|  A  |       Television picture height        |               100.0                |
|  B  |        Television picture width        |               133.33               |
|  C  |      Height of safe caption area       |                80.0                |
|  D  |       Width of safe caption area       |               106.67               |
|  E  | Vertical position of safe caption area |                10.0                |
|  F  |Horizontal position of safe caption area|               13.33                |

(13) *Special characters:* Displayable characters (except for “transparent space”) which require a two-byte sequence of one non-printing and one printing character. The non-printing byte varies depending on the data channel. Regular characters require unique one-byte codes which are the same in either data channel.

(14) *Text:* When written with an upper-case “T”, refers to the Text Mode. When written with a lower-case “t”, refers to any combination of displayable characters.

(15) *Transparent space:* Transmitted as a special character, it is a one-column-wide space behind which program video is always visible (except when a transparent space immediately precedes or follows a displayable character and solid box is needed to make that character legible).

[56 FR 27201, June 13, 1991, as amended at 57 FR 19094, May 4, 1992; 58 FR 44893, Aug. 25, 1993. Redesignated and amended at 77 FR 19515, 19518, Mar. 30, 2012; 78 FR 39627, July 2, 2013; 78 FR 77251, Dec. 20, 2013]