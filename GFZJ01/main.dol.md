This is the main executable of the game.

| Offset (hex) | Designation | Size | Datatype | Default Value | Description |
| --- | --- | --- | --- | --- | --- |
| 000000 | Offset to Text0 | 4 | uint32 | 0x00000100 | Becomes 0x8000aaf8 dol + (0x007AF8) during initialization |
| 000004 | Offset to Text1 | 4 | uint32 | 0x000025E0 | Becomes 0x8000aaf8 dol + (0x007AF8) during initialization |
| 000008 | Offset to Text2 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (dol + 0x007AF8) during initialization | 
|	00000C | Offset to Text3 | 4 | uint32	|	0x0	| Becomes 0x8000aaf8 (dol + 0x007AF8) during initialization |
|	000010 | Offset to Text4 | 4 | uint32	|	0x0	| Becomes 0x8000dd0c (dol + 0x00ad0c) during initialization |
| 000014 | Offset to Text5 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (dol + 0x007AF8) during initialization |
| 000018 | Offset to Text6 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (dol + 0x007AF8) during initialization |
| 00001C | Offset to Data0 | 4 | uint32 | 0x0008C540 | Becomes 0x8000aaf8 (dol + 0x007AF8), then 0, 0x8000c34c (0x00934c) during initialization |
| 000020 | Offset to Data1 | 4 | uint32 | 0x0008C560 | Becomes 0x8000aaf8 (dol + 0x007AF8), then 0, then 0x8000b2c0 (0x0082c0) during initialization |
| 000024 | Offset to Data2 | 4 | uint32 | 0x0008C580 | Becomes 0x8000aaf8 (dol + 0x007AF8), then 0 during initialization |
| 000028 | Offset to Data3 | 4 | uint32 | 0x00092500 | Becomes 0x8000aaf8 (dol + 0x007AF8), then 0 during initialization |
| 00002C | Offset to Data4 | 4 | uint32 | 0x00158180 | Becomes 0x8000aaf8 (dol + 0x007AF8), then 0 during initialization |
| 000030 | Offset to Data5 | 4 | uint32 | 0x00158480 | Becomes 0x8000aaf8 (dol + 0x007AF8), then 0 during initialization |
| 000034 | Offset to Data6 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (dol + 0x007AF8), then 0 during initialization |
| 000038 | Offset to Data7 | 4 | uint32 | 0x0 | |
| 00003C | Offset to Data8 | 4 | uint32 | 0x0 | |
| 000040 | Offset to Data9 | 4 | uint32 | 0x0 | Becomes 0x8000e7e4 (dol + 0x00b7e4) during initialization |
| 000044 | Offset to Data10 | 4 | uint32 | 0x0 | Becomes 0x8000e7e4 (dol + 0x00b7e4) during initialization |
| 000048 | Address to Text0 | 4 | uint32 | 0x80003100 | Becomes 0x8000e7e4 (dol + 0x00b7e4) during initialization |
| 00004C | Address to Text1 | 4 | uint32 | 0x800055E0 | Becomes 0x8000e7e4 (dol + 0x00b7e4) during initialization |
| 000050 | Address to Text2 | 4 | uint32 | 0x0 | Becomes 0x8000e7e4 (dol + 0x00b7e4) during initialization | 
|	000054 | Address to Text3 | 4 | uint32	|	0x0	| Becomes 0x8001e4f8 (dol + 0x1b4f8) during initialization |
|	000058 | Address to Text4 | 4 | uint32	|	0x0	| Becomes 0x8001eaf0 (dol + 0x1baf0) during initialization |
| 00005C | Address to Text5 | 4 | uint32 | 0x0 | Becomes 0x80028f9c (dol + 0x25f9c) during initialization |
| 000060 | Address to Text6 | 4 | uint32 | 0x0 | Becomes 0x8001e47c (dol + 0x1b47c) during initialization |
| 000064 | Address to Data0 | 4 | uint32 | 0x8008F540 | Becomes 0x8001491c (dol + 0x1191c) during initialization |
| 000068 | Address to Data1 | 4 | uint32 | 0x8008F560 | Becomes 0x800149e4 (dol + 0x119e4) during initialization |
| 00006C | Address to Data2 | 4 | uint32 | 0x8008F580 | Becomes 0x80014bfc (dol + 0x11bfc) during initialization |
| 000070 | Address to Data3 | 4 | uint32 | 0x80095500 | Becomes 0x8001491c (dol + 0x1191c) during initialization |
| 000074 | Address to Data4 | 4 | uint32 | 0x801A5C20 | Becomes 0x800149e4 (dol + 0x119e4) during initialization |
| 000078 | Address to Data5 | 4 | uint32 | 0x801A66C0 | Becomes 0x80014bfc (dol + 0x11bfc) during initialization |
| 00007C | Address to Data6 | 4 | uint32 | 0x0 | Becomes 0x8001491c (dol + 0x1191c) during initialization |
| 000080 | Address to Data7 | 4 | uint32 | 0x0 | Becomes 0x800149e4 (dol + 0x119e4) during initialization |
| 000084 | Address to Data8 | 4 | uint32 | 0x0 | Becomes 0x80031b4c (dol + 0x2eb4c) during initialization |
| 000088 | Address to Data9 | 4 | uint32 | 0x0 | Becomes 0x800343b8 (dol + 0x313b8) during initialization |
| 00008C | Address to Data10 | 4 | uint32 | 0x0 | Becomes 0x80034484 (dol + 0x31484) during initialization |
| 000090 | Size Text0 | 4 | uint32 | 0x000024E0 | Becomes 0x0, then 0x80011c70 (dol + 0x00ec70) during initialization |
| 000094 | Size Text1 | 4 | uint32 | 0x00089F60 | Becomes 0x0, then 0x80015fbc (dol + 0x012fbc) during initialization |
| 000098 | Size Text2 | 4 | uint32 | 0x00000000 | Becomes 0x0, then 0x8000f260 (dol + 0x00c260) during initialization |
| 00009C | Size Text3 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000A0 | Size Text4 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000A4 | Size Text5 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000A8 | Size Text6 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000AC | Size Data0 | 4 | uint32 | 0x00000020 | Becomes 0x0 during initialization |
| 0000B0 | Size Data1 | 4 | uint32 | 0x00000020 | Becomes 0x0 during initialization |
| 0000B4 | Size Data2 | 4 | uint32 | 0x00005F80 | Becomes 0x0 during initialization |
| 0000B8 | Size Data3 | 4 | uint32 | 0x000C5C80 | Becomes 0x0 during initialization |
| 0000BC | Size Data4 | 4 | uint32 | 0x00000300 | Becomes 0x0 during initialization |
| 0000C0 | Size Data5 | 4 | uint32 | 0x00000AC0 | Becomes 0x0, then 0xc1793891 during initialization |
| 0000C4 | Size Data6 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000C8 | Size Data7 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000CC | Size Data8 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000D0 | Size Data9 | 4 | uint32 | 0x00000000 | Becomes 0x0 during initialization |
| 0000D4 | Size Data10 | 4 | uint32 | 0x00000000 | Becomes 0x00178700 during initialization |
| 0000D8 | BBS Address | 4 | uint32 | 0x8015B180 | 0x006c80aa|
| 0000DC | BBS Size | 4 | uint32 | 0x0004C02C | 0xcb199d40 |
| 0000E0 | Entry Point Address | 4 | uint32 | 0x80003154 (dol + 0x0154) |  |
| 0000E4 | Padding | 4 | uint32 | 0x8015B180 |  |

| 000154 | Entrypoint | 4 | PPC | 0x4800015d | branch to dol+0x2b0 |
| 000158 | Branch to dol+400 | 4 | PPC | 0x480002a9 | always done after Register Clearance |



| 0002B0 - 00033F | Register Clearance | 0x9C | PPC |  | clears registers 0 - 31, sets r1 to 0x801b71b0, r2 to 0x801ae6c0, r13 to 0x801adc20, goto Entrypoint+4 |

| 000400 - 000413 | Set 14th msr flag  | 0x14 | PPC |  | or msr with 0x2000, move lr to r31 (dol+0x15c), goto dol+0x7B50 |

| 0005E4 | Metrowerks Credits | 0x30 | char[0x30] |  |  |

| 0070a4 - 0070ab | Move HID2 to r3 | 0x8 | PPC |  | and go back |
| 0070aC - 0070b3 | Move r3 to HID2 | 0x8 | PPC |  | and go back |



| 007b50 - 007b5F| Backup r0, r1 | 0x10 | PPC |  | backup r0, r1, update r1, branch to dol+0x70a4 |
| 007b60 - 007b67 | OR r3 with 0xA0000000 | 0x8 | PPC |  | and branch to dol+0x70aC |
| 007b68 | go to dol+0x8710 | 0x8 | PPC |  |  |

| 008710 - 0070ab | OR r3 HID0 with 0x800 | 0x10 | PPC |  | and go back |
