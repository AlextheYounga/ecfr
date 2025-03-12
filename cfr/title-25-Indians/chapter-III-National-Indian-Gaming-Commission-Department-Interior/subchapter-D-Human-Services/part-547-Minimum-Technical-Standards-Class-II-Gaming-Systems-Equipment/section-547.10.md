##### § 547.10 What are the minimum standards for Class II gaming system critical events? #####

(a) *Fault events.* (1) The following are fault events that must be capable of being recorded by the Class II gaming system:

|                Event                 |                                                                                                                                                Definition and action to be taken                                                                                                                                                 |
|--------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|         (i) Component fault          |                                                                                               Reported when a fault on a component is detected. When possible, this event message should indicate what the nature of the fault is.                                                                                               |
|(ii) Financial storage component full |                                                                           Reported when a financial instrument acceptor or dispenser includes storage, and it becomes full. This event message must indicate what financial storage component is full.                                                                           |
|(iii) Financial output component empty|                                                                                 Reported when a financial instrument dispenser is empty. The event message must indicate which financial output component is affected, and whether it is empty.                                                                                  |
|    (iv) Financial component fault    |                                                                                                                       Reported when an occurrence on a financial component results in a known fault state.                                                                                                                       |
|      (v) Critical memory error       |Some critical memory error has occurred. When a non-correctable critical memory error has occurred, the data on the Class II gaming system component can no longer be considered reliable. Accordingly, any game play on the affected component must cease immediately, and an appropriate message must be displayed, if possible.|
| (vi) Progressive communication fault |                                                                                                              If applicable; when communications with a progressive controller component is in a known fault state.                                                                                                               |
|  (vii) Program storage medium fault  |                                                     The software has failed its own internal security check or the medium itself has some fault. Any game play on the affected component must cease immediately, and an appropriate message must be displayed, if possible.                                                      |

(2) The occurrence of any event identified in paragraph (a)(1) of this section must be recorded.

(3) Upon clearing any event identified in paragraph (a)(1) of this section, the Class II gaming system must:

(i) Record that the fault condition has been cleared;

(ii) Ensure the integrity of all related accounting data; and

(iii) In the case of a malfunction, return a player's purchase or wager according to the rules of the game.

(b) *Door open/close events.* (1) In addition to the requirements of paragraph (a)(1) of this section, the Class II gaming system must perform the following for any component affected by any sensored door open event:

(i) Indicate that the state of a sensored door changes from closed to open or opened to closed;

(ii) Disable all financial instrument acceptance, unless a test mode is entered;

(iii) Disable game play on the affected player interface;

(iv) Disable player inputs on the affected player interface, unless test mode is entered; and

(v) Disable all financial instrument disbursement, unless a test mode is entered.

(2) The Class II gaming system may return the component to a ready to play state when all sensored doors are closed.

(c) *Non-fault events.* The following non-fault events are to be acted upon as described below, if applicable:

|                               Event                                |                                                                  Definition                                                                  |
|--------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|                (1) Player interface off during play                |                Indicates power has been lost during game play. This condition must be reported by the affected component(s).                 |
|                   (2) Player interface power on                    |               Indicates the player interface has been turned on. This condition must be reported by the affected component(s).               |
|(3) Financial instrument storage component container/stacker removed|Indicates that a financial instrument storage container has been removed. The event message must indicate which storage container was removed.|