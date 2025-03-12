##### § 547.13 What are the minimum technical standards for program storage media? #####

(a) *Removable program storage media.* All removable program storage media must maintain an internal checksum or signature of its contents. Verification of this checksum or signature is to be performed after every restart. If the verification fails, the affected Class II gaming system component(s) must lock up and enter a fault state.

(b) *Nonrewritable program storage media.* (1) All EPROMs and Programmable Logic Devices that have erasure windows must be fitted with covers over their erasure windows.

(2) All unused areas of EPROMs must be written with the inverse of the erased state (zero bits (00 hex) for most EPROMs), random data, or repeats of the program data.

(3) Flash memory storage components intended to have the same logical function as ROM, must be write-protected or otherwise protected from unauthorized modification.

(4) The write cycle must be closed or finished for all CD-ROMs such that it is not possible to write any further data to the CD.

(5) Write protected hard disks are permitted if the hardware means of enabling the write protect is easily viewable and can be sealed in place. Write protected hard disks are permitted using software write protection verifiable by a testing laboratory.

(c) *Writable and rewritable program storage media.* (1) Writable and rewritable program storage, such as hard disk drives, Flash memory, writable CD-ROMs, and writable DVDs, may be used provided that the software stored thereon may be verified using the mechanism provided pursuant to § 547.8(f).

(2) Program storage must be structured so there is a verifiable separation of fixed data (such as program, fixed parameters, DLLs) and variable data.

(d) *Identification of program storage media.* All program storage media that is not rewritable in circuit, (EPROM, CD-ROM) must be uniquely identified, displaying:

(1) Manufacturer;

(2) Program identifier;

(3) Program version number(s); and

(4) Location information, if critical (socket position 3 on the printed circuit board).