##### § 547.8 What are the minimum technical software standards applicable to Class II gaming systems? #####

(a) *Player interface displays.* (1) If not otherwise provided to the player, the player interface must display the following:

(i) The purchase or wager amount;

(ii) Game results; and

(iii) Any player credit balance.

(2) Between plays of any game and until the start of the next play, or until the player selects a new game option such as purchase or wager amount or card selection, whichever is earlier, if not otherwise provided to the player, the player interface must display:

(i) The total purchase or wager amount and all prizes and total credits won for the last game played;

(ii) The final results for the last game played; and

(iii) Any default purchase or wager amount for the next play.

(b) *Game initiation and play.* (1) Each game played on the Class II gaming system must follow and not deviate from a constant set of rules for each game provided to players pursuant to § 547.16. There must be no undisclosed changes of rules.

(2) The Class II gaming system may not alter or allow to be altered the card permutations used for play of a Class II game unless specifically chosen by the player prior to commitment to participate in the game. No duplicate cards may be sold for any common draw.

(3) No game play may commence, and no financial instrument or credit may be accepted on the affected player interface, in the presence of any fault condition that affects the outcome of the game, or while in test, audit, or lock-up mode.

(4) Each player must initiate his or her participation in the play of a game.

(c) *Audit mode.* (1) If an audit mode is provided, the Class II gaming system must, for those components actively involved in the audit:

(i) Provide all accounting functions required by § 547.9, by applicable provisions of any Commission regulations governing minimum internal control standards, and by any internal controls adopted by the tribe or TGRA;

(ii) Display player interface identification; and

(iii) Display software version or game identification.

(2) Audit mode must be accessible by a secure method such as an agent PIN, key, or other auditable access control.

(3) Accounting function data must be accessible by an agent at any time, except during a payout, during a handpay, or during play.

(4) The Class II gaming system must disable financial instrument acceptance on the affected player interface while in audit mode, except during financial instrument acceptance testing.

(d) *Last game recall.* The last game recall function must:

(1) Be retrievable at all times, other than when the recall component is involved in the play of a game, upon the operation of an external key-switch, entry of an audit card, or a similar method;

(2) Display the results of recalled games as originally displayed or in text representation so as to enable the TGRA or operator to clearly identify the sequences and results that occurred;

(3) Allow the Class II gaming system component providing game recall, upon return to normal game play mode, to restore any affected display to the positions, forms and values displayed before access to the game recall information; and

(4) Provide the following information for the current and previous four games played and must display:

(i) Play start time, end time, and date;

(ii) The total number of credits at the start of play;

(iii) The purchase or wager amount;

(iv) The total number of credits at the end of play;

(v) The total number of credits won as a result of the game recalled, and the value in dollars and cents for progressive prizes, if different;

(vi) For bingo games and games similar to bingo, also display:

(A) The card(s) used by the player;

(B) The identifier of the bingo game played;

(C) The numbers or other designations drawn, in the order that they were drawn;

(D) The numbers or other designations and prize patterns covered on each card;

(E) All prizes won by the player, including winning patterns, if any; and

(F) The unique identifier of the card on which prizes were won;

(vii) For pull-tab games only, also display:

(A) The result(s) of each pull-tab, displayed in the same pattern as on the tangible pull-tab;

(B) All prizes won by the player;

(C) The unique identifier of each pull tab; and

(D) Any other information necessary to fully reconstruct the current and four previous plays.

(e) *Voucher and credit transfer recall.* Notwithstanding the requirements of any other section in this part, a Class II gaming system must have the capacity to:

(1) Display the information specified in § 547.11(b)(5)(ii) through (vi) for the last five vouchers or coupons printed and the last five vouchers or coupons accepted; and

(2) Display a complete transaction history for the last five cashless transactions made and the last five cashless transactions accepted.

(f) *Software signature verification.* The manufacturer or developer of the Class II gaming system must provide to the testing laboratory and to the TGRA an industry-standard methodology, acceptable to the TGRA, for verifying the Class II gaming system game software. For example, for game software stored on rewritable media, such methodologies include signature algorithms and hashing formulas such as SHA-1.

(g) *Test, diagnostic, and demonstration modes.* If test, diagnostic, and/or demonstration modes are provided, the Class II gaming system must, for those components actively involved in the test, diagnostic, or demonstration mode:

(1) Clearly indicate when that component is in the test, diagnostic, or demonstration mode;

(2) Not alter financial data on that component other than temporary data;

(3) Only be available after entering a specific mode;

(4) Disable credit acceptance and payment unless credit acceptance or payment is being tested; and

(5) Terminate all mode-specific functions upon exiting a mode.

(h) *Multigame.* If multiple games are offered for player selection at the player interface, the player interface must:

(1) Provide a display of available games;

(2) Provide the means of selecting among them;

(3) Display the full amount of the player's credit balance;

(4) Identify the game selected or being played; and

(5) Not force the play of a game after its selection.

(i) *Program interruption and resumption.* The Class II gaming system software must be designed so that upon resumption following any interruption, the system:

(1) Is able to return to a known state;

(2) Must check for any fault condition;

(3) Must verify the integrity of data stored in critical memory;

(4) Must return the purchase or wager amount to the player in accordance with the rules of the game; and

(5) Must detect any change or corruption in the Class II gaming system software.

(j) *Class II gaming system components acting as progressive controllers.* This paragraph applies to progressive controllers and components acting as progressive controllers in Class II gaming systems.

(1) Modification of progressive parameters must be conducted in a secure manner approved by the TGRA. Such parameters may include:

(i) Increment value;

(ii) Secondary pool increment(s);

(iii) Reset amount(s);

(iv) Maximum value(s); and

(v) Identity of participating player interfaces.

(2) The Class II gaming system component or other progressive controller must provide a means of creating a progressive balancing report for each progressive link it controls. At a minimum, that report must provide balancing of the changes of the progressive amount, including progressive prizes won, for all participating player interfaces versus current progressive amount(s), plus progressive prizes. In addition, the report must account for, and not be made inaccurate by, unusual events such as:

(i) Class II gaming system critical memory clears;

(ii) Modification, alteration, or deletion of progressive prizes;

(iii) Offline equipment; or

(iv) Multiple site progressive prizes.

(k) *Critical memory.* (1) Critical memory may be located anywhere within the Class II gaming system. Critical memory is any memory that maintains any of the following data:

(i) Accounting data;

(ii) Current credits;

(iii) Configuration data;

(iv) Last game play recall information required by paragraph (d) of this section;

(v) Game play recall information for the current game play, if incomplete;

(vi) Software state (the last normal state software was in before interruption);

(vii) RNG seed(s), if necessary for maintaining integrity;

(viii) Encryption keys, if necessary for maintaining integrity;

(ix) Progressive prize parameters and current values;

(x) The five most recent financial instruments accepted by type, excluding coins and tokens;

(xi) The five most recent financial instruments dispensed by type, excluding coins and tokens; and

(xii) The five most recent cashless transactions paid and the five most recent cashless transactions accepted.

(2) Critical memory must be maintained using a methodology that enables errors to be identified and acted upon. All accounting and recall functions must be verified as necessary to ensure their ongoing integrity.

(3) The validity of affected data stored in critical memory must be checked after each of the following events:

(i) Every restart;

(ii) Each attendant paid win;

(iii) Each attendant paid progressive win;

(iv) Each sensored door closure; and

(v) Every reconfiguration, download, or change of prize schedule or denomination requiring operator intervention or action.

(l) *Secured access.* Class II gaming systems that use a logon or other means of secured access must include a user account lockout after a predetermined number of consecutive failed attempts to access the Class II gaming system.