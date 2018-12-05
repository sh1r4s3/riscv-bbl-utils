This is the utils for RISC-V Berkeley Bootloader (BBL).

- bbl-patch -- this util allows one to patch Berkeley Bootloader (bbl) image file with kernel included to it.
- mkbbl -- this script uses objcopy to strip vmlinux ELF and obtain raw binary of a kernel. Then it will concatenate bbl and raw kernel binary, patch it and out to a new binary file.

Author: Nikita Ermakov <arei@altlinux.org> <coffe92@gmail.com>
