This is the main executable of the game.

| Offset (hex) | Designation | Size | Datatype | Default Value | Description |
| --- | --- | --- | --- | --- | --- |
| 000000 | Offset to Text0 | 4 | uint32 | 0x00000100 | Becomes 0x8000aaf8 (0x007AF8 dol location) during initialization |
| 000004 | Offset to Text1 | 4 | uint32 | 0x000025E0 | Becomes 0x8000aaf8 (0x007AF8 dol location) during initialization |
| 000008 | Offset to Text2 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (0x007AF8 dol location) during initialization | 
|	00000C | Offset to Text3 | 4 | uint32	|	0x0	| Becomes 0x8000aaf8 (0x007AF8 dol location) during initialization |
|	000010 | Offset to Text4 | 4 | uint32	|	0x0	| Becomes 0x8000dd0c (0x00ad0c dol location) during initialization |
| 000014 | Offset to Text5 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (0x007AF8 dol location) during initialization |
| 000018 | Offset to Text6 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (0x007AF8 dol location) during initialization |
| 00001C | Offset to Data0 | 4 | uint32 | 0x0008C540 | Becomes 0x8000aaf8 (0x007AF8 dol location), then 0, 0x8000c34c (0x00934c dol location) during initialization |
| 000020 | Offset to Data1 | 4 | uint32 | 0x0008C560 | Becomes 0x8000aaf8 (0x007AF8 dol location), then 0, then 0x8000b2c0 (0x0082c0 dol location) during initialization |
| 000024 | Offset to Data2 | 4 | uint32 | 0x0008C580 | Becomes 0x8000aaf8 (0x007AF8 dol location), then 0 during initialization |
| 000028 | Offset to Data3 | 4 | uint32 | 0x00092500 | Becomes 0x8000aaf8 (0x007AF8 dol location), then 0 during initialization |
| 00002C | Offset to Data4 | 4 | uint32 | 0x00158180 | Becomes 0x8000aaf8 (0x007AF8 dol location), then 0 during initialization |
| 000030 | Offset to Data5 | 4 | uint32 | 0x00158480 | Becomes 0x8000aaf8 (0x007AF8 dol location), then 0 during initialization |
| 000034 | Offset to Data6 | 4 | uint32 | 0x0 | Becomes 0x8000aaf8 (0x007AF8 dol location), then 0 during initialization |
| 000038 | Offset to Data7 | 4 | uint32 | 0x0 | |
| 00003C | Offset to Data8 | 4 | uint32 | 0x0 | |
| 000040 | Offset to Data9 | 4 | uint32 | 0x0 | Becomes 0x8000e7e4 (0x00b7e4 dol location) during initialization |
| 000044 | Offset to Data10 | 4 | uint32 | 0x0 | Becomes 0x8000e7e4 (0x00b7e4 dol location) during initialization |
| 000048 | Address to Text0 | 4 | uint32 | 0x80003100 | Becomes 0x8000e7e4 (0x00b7e4 dol location) during initialization |
| 00004C | Address to Text1 | 4 | uint32 | 0x800055E0 | Becomes 0x8000e7e4 (0x00b7e4 dol location) during initialization |
| 000050 | Address to Text2 | 4 | uint32 | 0x0 | Becomes 0x8000e7e4 (0x00b7e4 dol location) during initialization | 
|	000054 | Address to Text3 | 4 | uint32	|	0x0	| Becomes 0x8001e4f8 (0x1b4f8 dol location) during initialization |
|	000058 | Address to Text4 | 4 | uint32	|	0x0	| Becomes 0x8001eaf0 (0x1baf0 dol location) during initialization |
| 00005C | Address to Text5 | 4 | uint32 | 0x0 | Becomes 0x80028f9c (0x25f9c dol location) during initialization |
| 000060 | Address to Text6 | 4 | uint32 | 0x0 | Becomes 0x8001e47c (0x1b47c dol location) during initialization |
| 000064 | Address to Data0 | 4 | uint32 | 0x8008F540 | Becomes 0x8001491c (0x1191c dol location) during initialization |
| 000068 | Address to Data1 | 4 | uint32 | 0x8008F560 | Becomes 0x800149e4 (0x119e4 dol location) during initialization |
| 00006C | Address to Data2 | 4 | uint32 | 0x8008F580 | Becomes 0x80014bfc (0x11bfc dol location) during initialization |
| 000070 | Address to Data3 | 4 | uint32 | 0x80095500 | Becomes 0x8001491c (0x1191c dol location) during initialization |
| 000074 | Address to Data4 | 4 | uint32 | 0x801A5C20 | Becomes 0x800149e4 (0x119e4 dol location) during initialization |
| 000078 | Address to Data5 | 4 | uint32 | 0x801A66C0 | Becomes 0x80014bfc (0x11bfc dol location) during initialization |
| 00007C | Address to Data6 | 4 | uint32 | 0x0 | Becomes 0x8001491c (0x1191c dol location) during initialization |
| 000080 | Address to Data7 | 4 | uint32 | 0x0 | Becomes 0x800149e4 (0x119e4 dol location) during initialization |
| 000084 | Address to Data8 | 4 | uint32 | 0x0 | Becomes 0x80031b4c (0x2eb4c dol location) during initialization |
| 000088 | Address to Data9 | 4 | uint32 | 0x0 | Becomes 0x800343b8 (0x313b8 dol location) during initialization |
| 00008C | Address to Data10 | 4 | uint32 | 0x0 | Becomes 0x80034484 (0x31484 dol location) during initialization |
