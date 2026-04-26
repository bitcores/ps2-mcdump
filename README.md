# ps2-mcdump
PS2 memory card dumping tool

Dumps the entire contents of the memory card in slot 2 into memory where it can be dumped with a tool like ps2client. Displays DONE message when complete or reboots to BIOS if failure.

Contents are dumped to memory position 0x20_0000, 8MB card can be dumped with the following command

./ps2client -h <ps2> dumpmem 2097152 8650752 dump.txt

16MB cards MAY be supported, higher will not fit in RAM

No guarantees. Use at your own risk.
