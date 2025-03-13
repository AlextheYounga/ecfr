##### § 79.102 Closed caption decoder requirements for digital television receivers and converter boxes. #####

(a)(1) Effective July 1, 2002, all digital television receivers with picture screens in the 4:3 aspect ratio with picture screens measuring 13 inches or larger diagonally, all digital television receivers with picture screens in the 16:9 aspect ratio measuring 7.8 inches or larger vertically and all separately sold DTV tuners shipped in interstate commerce or manufactured in the United States shall comply with the provisions of this section.

Note to paragraph (a)(1):

This paragraph places no restrictions on the shipping or sale of digital television receivers that were manufactured before July 1, 2002.

(2) Effective July 1, 2002, DTV converter boxes that allow digitally transmitted television signals to be displayed on analog receivers shall pass available analog caption information to the attached receiver in a form recognizable by that receiver's built-in caption decoder circuitry.

Note to paragraph (a)(2):

This paragraph places no restrictions on the shipping or sale of DTV converter boxes that were manufactured before July 1, 2002.

(3) Effective January 1, 2014, all digital television receivers and all separately sold DTV tuners shipped in interstate commerce or manufactured in the United States shall comply with the provisions of this section, if technically feasible, except that digital television receivers that use a picture screens less than 13 inches in size must comply with the provisions of this section only if doing so is achievable pursuant to § 79.103(b)(3).

Note to paragraph (a)(3):

This paragraph places no restrictions on the importing, shipping, or sale of digital television receivers and separately sold DTV tuners that were manufactured before January 1, 2014.

(b) Digital television receivers and tuners must be capable of decoding closed captioning information that is delivered pursuant to EIA-708-B: “Digital Television (DTV) Closed Captioning” (incorporated by reference, *see* § 79.100).

(c) *Services.* (1) Decoders must be capable of decoding and processing data for the six standard services, Caption Service #1 through Caption Service #6.

(2) Decoders that rely on Program and System Information Protocol data to implement closed captioning functions must be capable of decoding and processing the Caption Service Directory data. Such decoders must be capable of decoding all Caption Channel Block Headers consisting of Standard Service Headers, Extended Service Block Headers, and Null Block headers. However, decoding of the data is required only for Standard Service Blocks (Service IDs \<-6), and then only if the characters for the corresponding language are supported. The decoders must be able to display the directory for services 1 through 6.

(d) *Code space organization.* (1) Decoders must support Code Space C0, G0, C1, and G1 in their entirety.

![](/graphics/er29se00.000.gif)

(2) The following characters within code space G2 must be supported:

(i) Transparent space (TSP).

(ii) Non-breaking transparent space (NBTSP).

(iii) Solid block ( ).

(iv) Trademark symbol (TM).

(v) Latin-1 characters Š, Œ, š, œ, Ÿ.

(3) The substitutions in Table 2 are to be made if a decoder does not support the remaining G2 characters.

|               G2 Character                |           Substitute with           |
|-------------------------------------------|-------------------------------------|
|Open single quote (‘), G2 char code 0 × 31 |G0 single quote (‘), char code 0 × 27|
|Close single quote (’), G2 char code 0 × 32|G0 single quote (’), char code 0 × 27|
|Open double quote (“), G2 char code 0 × 33 |G0 double quote (“), char code 0 × 22|
|Close double quote (”), G2 char code 0 × 34|G0 double quote (”), char code 0 × 22|
|   Bold bullet (•), G2 char code 0 × 35    |   G1 bullet (•), char code 0 × B7   |
|   Elipsis (. . .), G2 char code 0 × 25    |G0 underscore (\_), char code 0 × 5F |
|   One-eighth (1/8), G2 char code 0 × 76   |G0 percent sign (%), char code 0 × 25|
| Three-eighths (3/8), G2 char code 0 × 77  |G0 percent sign (%), char code 0 × 25|
|  Five-eighths (5/8), G2 char code 0 × 78  |G0 percent sign (%), char code 0 × 25|
| Seven-eighths (7/8), G2 char code 0 × 79  |G0 percent sign (%), char code 0 × 25|
| Vertical border (|), G2 char code 0 × 7A  |   G0 stroke (|), char code 0 × 7C   |
|Upper-right border (⌉), G2 char code 0 × 7B|    G0 dash (-), char code 0 × 2D    |
|Lower-left border (⌊), G2 char code 0 × 7C |    G0 dash (-), char code 0 × 2D    |
|Horizontal border (―), G2 char code 0 × 7D |    G0 dash (-), char code 0 × 2D    |
|Lower-right border (⌋), G2 char code 0 × 7E|    G0 dash (-), char code 0 × 2D    |
|Upper-left border (⌈), G2 char code 0 × 7F |    G0 dash (-), char code 0 × 2D    |

(4) Support for code spaces C2, C3, and G3 is optional. All unsupported graphic symbols in the G3 code space are to be substituted with the G0 underscore character (\_), char code 0 × 5F.

(e) *Screen coordinates.* Table 3 specifies the screen coordinate resolutions and limits for anchor point positioning in 4:3 and 16:9 display formats, and the number of characters per row.

|                                                                              Screen aspect ratio                                                                               |Maximum anchor position resolution|Minimum anchor position resolution|Maximum displayed rows|Maximum characters per row|
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------|----------------------------------|----------------------|--------------------------|
|                                                                                      4:3                                                                                       |            75v × 160h            |            15v × 32h             |          4           |            32            |
|                                                                                      16:9                                                                                      |            75v × 210h            |            15v × 42h             |          4           |            42            |
|                                                                                     Other                                                                                      |          75v × (5 × H)           |            15v × H\*             |          4           |       <sup>1</sup>       |
|<sup>1</sup> H = 32 × (the width of the screen in relation to a 4:3 display). For example, the 16:9 format is 1/3 wider than a 4:3 display; thus, H = 32 \* 4/3 = 42.667, or 42.|                                  |                                  |                      |                          |

(1) This means that the minimum grid resolution for a 4:3 aspect ratio instrument is 15 vertical positions × 32 horizontal positions. This minimum grid resolution for 16:9 ratio instrument is 15 vertical positions × 42 horizontal positions. These minimum grid sizes are to cover the entire safe-title area of the corresponding screen.

(2) The minimum coordinates equate to a 1/5 reduction in the maximum horizontal and vertical grid resolution coordinates. Caption providers are to use the maximum coordinate system values when specifying anchor point positions. Decoders using the minimum resolution are to divide the provided horizontal and vertical screen coordinates by 5 to derive the equivalent minimum coordinates.

(3) Any caption targeted for both 4:3 and 16:9 instruments is limited to 32 contiguous characters per row. If a caption is received by a 4:3 instrument that is targeted for a 16:9 display only, or requires a window width greater than 32 characters, then the caption may be completely disregarded by the decoder. 16:9 instruments should be able to process and display captions intended for 4:3 displays, providing all other minimum recommendations are met.

(4) If the resulting size of any window is larger than the safe title area for the corresponding display's aspect ratio, then this window will be completely disregarded.

(f) *Caption windows.* (1) Decoders need to display no more than 4 rows of captions on the screen at any given time, regardless of the number of windows displayed. This implies that no more than 4 windows can be displayed at any given time (with each having only one caption row). However, decoders should maintain storage to support a minimum total of 8 rows of captions. This storage is needed for the worst-case support of a displayed window with 4 rows of captioning and a non-displayed window which is buffering the incoming rows for the next 4-row caption. As implied above, the maximum number of windows that may be displayed at any one time by a minimum decoder implementation is 4. If more than 4 windows are defined in the caption stream, the decoder may disregard the youngest and lowest priority window definition(s). Caption providers must be aware of this limitation, and either restrict the total number of windows used or accept that some windows will not be displayed.

(2) Decoders do not need to support overlapped windows. If a window overlaps another window, the overlapped window need not be displayed by the decoder.

(3) At a minimum, decoders will assume that all windows have rows and columns “locked”. This implies that if a decoder implements the SMALL pen-size, then word-“un”wrapping, when shrinking captions, need not be implemented. Also, if a decoder implements the LARGE pen size, then word wrapping (when enlarging captions) need not be implemented.

(4) Whenever possible, the receiver should render embedded carriage returns as line breaks, since these carriage returns indicate an important aspect of the caption's formatting as determined by the service provider. However, it may sometimes be necessary for the receiver to ignore embedded line breaks. For example, if a caption is to appear in a larger font, and if its window's rows and/or columns are unlocked, the rows of text may need to become longer or shorter to fit within the allocated space. Such automatic reformatting of a caption is known as “word wrap.” If decoders support word-wrapping, it must be implemented as follows:

(i) The receiver should follow standard typographic practice when implementing word wrap. Potential breaking points (word-wrapping points) are indicated by the space character (20h) and by the hyphen character (2Dh).

(ii) If a row is to be broken at a space, the receiver should remove the space from the caption display. If a row is to be broken after a hyphen, the hyphen should be retained.

(iii) If an embedded return is to be removed, it should usually be replaced with a space. However, if the character to the left of the embedded return is a hyphen, the embedded return should be removed but NOT replaced with a space.

(iv) This specification does not include optional hyphens, nor does it provide for any form of automatic hyphenation. No non-breaking hyphen is defined. The non-breaking space (A0h in the G1 code set) and the non-breaking transparent space (21h in the G2 code set) should not be considered as potential line breaks.

(v) If a single word exceeds the length of a row, the word should be placed at the start of a new row, broken at the character following the last character that fits on the row, and continued with further breaks if needed.

(g) *Window text painting.* (1) All decoders should implement “left”, “right”, and “center” caption-text justification. Implementation of “full” justification is optional. If “full” justification is not implemented, fully justified captions should be treated as though they are “left” justified.

(i) For “left” justification, decoders should display any portion of a received row of text when it is received. For “center”, “right”, and “full” justification, decoders may display any portion of a received row of text when it is received, or may delay display of a received row of text until reception of a row completion indicator. A row completion indicator is defined as receipt of a CR, ETX or any other command, except SetPenColor, SetPenAttributes, or SetPenLocation where the pen relocation is within the same row.

(ii) Receipt of a character for a displayed row which already contains text with “center”, “right” or “full” justification will cause the row to be cleared prior to the display of the newly received character and any subsequent characters. Receipt of a justification command which changes the last received justification for a given window will cause the window to be cleared.

(2) At a minimum, decoders must support LEFT\_TO\_RIGHT printing.

(3) At a minimum, decoders must support BOTTOM\_TO\_TOP scrolling. For windows sharing the same horizontal scan lines on the display, scrolling may be disabled.

(4) At a minimum, decoders must support the same recommended practices for scroll rate as is provided for NTSC closed-captioning.

(5) At a minimum, decoders must support the same recommended practices for smooth scrolling as is provided for NTSC closed-captioning.

(6) At a minimum, decoders must implement the “snap” window display effect. If the window “fade” and “wipe” effects are not implemented, then the decoder will “snap” all windows when they are to be displayed, and the “effect speed” parameter is ignored.

(h) *Window colors and borders.* At a minimum, decoders must implement borderless windows with solid, black backgrounds (*i.e.*, border type = NONE, fill color = (0,0,0), fill opacity = SOLID), and borderless transparent windows (*i.e.*, border type = NONE, fill opacity = TRANSPARENT).

(i) *Predefined window and pen styles.* Predefined Window Style and Pen Style ID's may be provided in the DefineWindow command. At a minimum, decoders should implement Predefined Window Attribute Style 1 and Predefined Pen Attribute Style 1, as shown in Table 4 and Table 5, respectively.

|Style ID #|Justify|Print direction|Scroll  <br/>direction|Word wrap|Display  <br/>effect|Effect  <br/>direction|Effect  <br/>speed| Fill color  |Fill opacity|Border type|Border color|               Usage                |
|----------|-------|---------------|----------------------|---------|--------------------|----------------------|------------------|-------------|------------|-----------|------------|------------------------------------|
|    1     | Left  | Left-to-right |    Bottom-to-top     |   No    |        Snap        |         n/a          |       n/a        |(0,0,0) Black|   Solid    |   None    |    n/a     |     NTSC Style PopUp Captions      |
|    2     | Left  | Left-to-right |    Bottom-to-top     |   No    |        Snap        |         n/a          |       n/a        |     n/a     |Transparent |   None    |    n/a     |PopUp Captions w/o Black Background |
|    3     | Cntr  | Left-to-right |    Bottom-to-top     |   No    |        Snap        |         n/a          |       n/a        |(0,0,0) Black|   Solid    |   None    |    n/a     | NTSC Style Centered PopUp Captions |
|    4     | Left  | Left-to-right |    Bottom-to-top     |   Yes   |        Snap        |         n/a          |       n/a        |(0,0,0) Black|   Solid    |   None    |    n/a     |     NTSC Style RollUp Captions     |
|    5     | Left  | Left-to-right |    Bottom-to-top     |   Yes   |        Snap        |         n/a          |       n/a        |     n/a     |Transparent |   None    |    n/a     |RollUp Captions w/o Black Background|
|    6     | Cntr  | Left-to-right |    Bottom-to-top     |   Yes   |        Snap        |         n/a          |       n/a        |(0,0,0) Black|   Solid    |   None    |    n/a     |NTSC Style Centered RollUp Captions |
|    7     | Left  | Top-to-bottom |    Right-to-left     |   No    |        Snap        |         n/a          |       n/a        |(0,0,0) Black|   Solid    |   None    |    n/a     |            Ticker Tape             |

|             Predefined style ID             |Pen size|Font style|Offset|Italics|Underline|Edge type|Foregrnd color|Foregrnd opacity|Backgrnd color|Backgrnd opacity| Edge color  |                Usage                |
|---------------------------------------------|--------|----------|------|-------|---------|---------|--------------|----------------|--------------|----------------|-------------|-------------------------------------|
|                      1                      | Stndr  |    0     |Normal|  No   |   No    |  None   |(2,2,2) White |     Solid      |(0,0,0) Black |     Solid      |     n/a     |        Default NTSC Style\*         |
|                      2                      | Stndr  |    1     |Normal|  No   |   No    |  None   |   (2,2,2)    |     Solid      |(0,0,0) White |     Solid      |     n/a     |      NTSC Style\* Mono w/Serif      |
|                      3                      | Stndr  |    2     |Normal|  No   |   No    |  None   |(2,2,2) White |     Solid      |(0,0,0) Black |     Solid      |     n/a     |     NTSC Style\* Prop w/ Serif      |
|                      4                      | Stndr  |    3     |Normal|  No   |   No    |  None   |(2,2,2) White |     Solid      |(0,0,0) Black |     Solid      |     n/a     |     NTSC Style\* Mono w/o Serif     |
|                      5                      | Stndr  |    4     |Normal|  No   |   No    |  None   |(2,2,2) White |     Solid      |(0,0,0) Black |     Solid      |     n/a     |     NTSC Style\* Prop w/o Serif     |
|                      6                      | Stndr  |    3     |Normal|  No   |   No    | Unifrm  |(2,2,2) White |     Solid      |     n/a      |  Transparent   |(0,0,0) Black|Mono w/o Serif, Bordered Text, No BG |
|                      7                      | Stndr  |    4     |Normal|  No   |   No    | Unifrm  |(2,2,2) White |     Solid      |     n/a      |  Transparent   |(0,0,0) Black|Prop. w/o Serif, Bordered Text, No BG|
|\*“NTSC Style”—White Text on Black Background|        |          |      |       |         |         |              |                |              |                |             |                                     |

(j) *Pen size.* (1) Decoders must support the standard, large, and small pen sizes and must allow the caption provider to choose a pen size and allow the viewer to choose an alternative size. The STANDARD pen size should be implemented such that the height of the tallest character in any implemented font is no taller than 1/15 of the height of the safe-title area, and the width of the widest character is no wider than 1/32 of the width of the safe-title area for 4:3 displays and 1/42 of the safe-title area width for 16:9 displays.

(2) The LARGE pen size should be implemented such that the width of the widest character in any implemented font is no wider than 1/32 of the safe-title area for 16:9 displays. This recommendation allows for captions to grow to a LARGE pen size without having to reformat the caption since no caption will have more than 32 characters per row.

(k) *Font styles.* (1) Decoders must support the eight fonts listed below. Caption providers may specify 1 of these 8 font styles to be used to write caption text. The styles specified in the “font style” parameter of the SetPenAttributes command are numbered from 0 through 7. The following is a list of the 8 required font styles. For information purposes only, each font style references one or more popular fonts which embody the characteristics of the style:

(i) 0—Default (undefined)

(ii) 1—Monospaced with serifs (similar to Courier)

(iii) 2—Proportionally spaced with serifs (similar to Times New Roman)

(iv) 3—Monospaced without serifs (similar to Helvetica Monospaced)

(v) 4—Proportionally spaced without serifs (similar to Arial and Swiss)

(vi) 5—Casual font type (similar to Dom and Impress)

(vii) 6—Cursive font type (similar to Coronet and Marigold)

(viii) 7—Small capitals (similar to Engravers Gothic)

(2) Font styles may be implemented in any typeface which the decoder manufacturer deems to be a readable rendition of the font style, and need not be in the exact typefaces given in the example above. Decoders must include the ability for consumers to choose among the eight fonts. The decoder must display the font chosen by the caption provider unless the viewer chooses a different font.

(l) *Character offsetting.* Decoders need not implement the character offsetting (*i.e.,* subscript and superscript) pen attributes.

(m) *Pen styles.* At a minimum, decoders must implement normal, italic, and underline pen styles.

(n) *Foreground color and opacity.* (1) At a minimum, decoders must implement transparent, translucent, solid and flashing character foreground type attributes.

(2) At a minimum, decoders must implement the following character foreground colors: white, black, red, green, blue, yellow, magenta and cyan.

(3) Caption providers may specify the color/opacity. Decoders must include the ability for consumers to choose among the color/opacity options. The decoder must display the color/opacity chosen by the caption provider unless the viewer chooses otherwise.

(o) *Background color and opacity.* (1) Decoders must implement the following background colors: white, black, red, green, blue, yellow, magenta and cyan. It is recommended that this background is extended beyond the character foreground to a degree that the foreground is separated from the underlying video by a sufficient number of background pixels to insure the foreground is separated from the background.

(2) Decoders must implement transparent, translucent, solid and flashing background type attributes. Caption providers may specify the color/opacity. Decoders must include the ability for consumers to choose among the color/opacity options. The decoder must display the color/opacity chosen by the caption provider unless the viewer chooses otherwise.

(p) *Character edges.* Decoders must implement separate edge color and type attribute control.

(q) *Color representation.* (1) At a minimum, decoders must support the 8 colors listed in Table 6.

| Color |Red|Green|Blue|
|-------|---|-----|----|
| Black | 0 |  0  | 0  |
| White | 2 |  2  | 2  |
|  Red  | 2 |  0  | 0  |
| Green | 0 |  2  | 0  |
| Blue  | 0 |  0  | 2  |
|Yellow | 2 |  2  | 0  |
|Magenta| 2 |  0  | 2  |
| Cyan  | 0 |  2  | 2  |

(2)(i) When a decoder supporting this Minimum Color List receives an RGB value not in the list, it will map the received value to one of the values in the list via the following algorithm:

(A) All one (1) values are to be changed to 0.

(B) All two (2) values are to remain unchanged.

(C) All three (3) values are to be changed to 2.

(ii) For example, the RGB value (1,2,3) will be mapped to (0,2,2), (3,3,3) will be mapped to (2,2,2) and (1,1,1) will be mapped to (0,0,0).

(3) Table 7 is an alternative minimum color list table supporting 22 colors.

|    Color     |Red|Green|Blue|
|--------------|---|-----|----|
|    Black     | 0 |  0  | 0  |
|     Gray     | 1 |  1  | 1  |
|    White     | 2 |  2  | 2  |
| Bright White | 3 |  3  | 3  |
|   Dark Red   | 1 |  0  | 0  |
|     Red      | 2 |  0  | 0  |
|  Bright Red  | 3 |  0  | 0  |
|  Dark Green  | 0 |  1  | 0  |
|    Green     | 0 |  2  | 0  |
| Bright Green | 0 |  3  | 0  |
|  Dark Blue   | 0 |  0  | 1  |
|     Blue     | 0 |  0  | 2  |
| Bright Blue  | 0 |  0  | 3  |
| Dark Yellow  | 1 |  1  | 0  |
|    Yellow    | 2 |  2  | 0  |
|Bright Yellow | 3 |  3  | 0  |
| Dark Magenta | 1 |  0  | 1  |
|   Magenta    | 2 |  0  | 2  |
|Bright Magenta| 3 |  0  | 3  |
|  Dark Cyan   | 0 |  1  | 1  |
|     Cyan     | 0 |  2  | 2  |
| Bright Cyan  | 0 |  3  | 3  |

(i) When a decoder supporting the Alternative Minimum Color List in Table 7 receives an RGB value not in the list (*i.e.*, an RGB value whose non-zero elements are not the same value), it will map the received value to one of the values in the list via the following algorithm:

(A) For RGB values with all elements non-zero and different—e.g., (1,2,3), (3,2,1), and (2,1,3), the 1 value will be changed to 0, the 2 value will remain unchanged, and the 3 value will be changed to 2.

(B) For RGB values with all elements non-zero and with two common elements—e.g., (3,1,3), (2,1,2), and (2,2,3), if the common elements are 3 and the uncommon one is 1, then the 1 elements is changed to 0; e.g. (3,1,3) → (3,0,3). If the common elements are 1 and the uncommon element is 3, then the 1 elements are changed to 0, and the 3 element is changed to 2; e.g. (1,3,1) → (0,2,0). In all other cases, the uncommon element is changed to the common value; e.g., (2,2,3) → (2,2,2), (1,2,1) → (1,1,1), and (3,2,3) → (3,3,3).

(ii) All decoders not supporting either one of the two color lists described above, must support the full 64 possible RGB color value combinations.

(r) *Character rendition considerations.* In NTSC Closed Captioning, decoders were required to insert leading and trailing spaces on each caption row. There were two reasons for this requirement:

(1) To provide a buffer so that the first and last characters of a caption row do not fall outside the safe title area, and

(2) To provide a black border on each side of a character so that the “white” leading pixels of the first character on a row and the trailing “white” pixels of the last character on a row do not bleed into the underlying video.

(i) Since caption windows are required to reside in the safe title area of the DTV screen, reason 1 (above) is not applicable to DTVCC captions.

(ii) The attributes available in the SetPenAttributes command for character rendition (e.g., character background and edge attributes) provide unlimited flexibility to the caption provider when describing caption text in an ideal decoder implementation. However, manufacturers need not implement all pen attributes. Thus it is recommended that no matter what the level of implementation, decoder manufacturers should take into account the readability of all caption text against a variety of all video backgrounds, and should implement some automatic character delineation when the individual control of character foreground, background and edge is not supported.

(s) *Service synchronization.* Service Input Buffers must be at least 128 bytes in size. Caption providers must keep this lower limit in mind when following Delay commands with other commands and window text. In other words, no more than 128 bytes of DTVCC commands and text should be transmitted (encoded) before a pending Delay command's delay interval expires.

(t) *Settings.* Decoders must include an option that permits a viewer to choose a setting that will display captions as intended by the caption provider (a default). Decoders must also include an option that allows a viewer's chosen settings to remain until the viewer chooses to alter these settings, including periods when the television is turned off.

[65 FR 58471, Sept. 29, 2000, as amended at 69 FR 2849, Jan. 21, 2004. Redesignated and amended at 77 FR 19515, 19518, Mar. 30, 2012; 78 FR 39627, July 2, 2013]