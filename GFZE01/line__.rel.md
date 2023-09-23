This file is usually compressed to a .lz archive and encrypted. line__crypt can be used to decrypt it to a .lz archive and encrypt it again. GXPand can be used to unpack the .lz to a .rel and vice versa. F-Zero AX has this file within its main.dol and does not need any conversion or compression.

| Offset (hex) | Designation | Size | Datatype | Default Value | Description |
| --- | --- | --- | --- | --- | --- |
| 000000 | .rel file header | 0x4C | binary | | |
| 00004C | Additional rel info | 0x90 | binary | | |
| 0000DC | Unknown function | 0x15F62C | PPC | | | 
|	079670	|	Generate pointer to minimap parameter struct	|	0x38	|	PPC	|		|		|
|	0C3E2C |	Difficulty Fallback Instruction	|	4	|	PPC	|	0x38000001 (li r0, 1)	|	Sets difficulty to 1 (Standard)	|
| 15F708 | ?  | 0x198 | ? |  |
|	15F8A0	|	Render Distance	|	4	|	float32	|	90000.0	|	 |
| 15F8A4 | ?  | 0x5C | ? |  |
|	15F900	|	High Speed SFX threshold	|	4	|	float32	|	16.9333	|		|
| 15F904 | ?  | 0xC | ? |  |
|	15F910	|	Camera Parameter	|	4	|	float32	|	0.3	|		|
| 15F914 | ?  | 0x6C0 | ? |  |
|	15FFD4	|	Turn Multiplier?	|	4	|	float32	|	1.5	|		|
| 15FFD8 | ?  | 0x6C0 | ? |  |
|	15FFE4	|	Top Speed Multiplier?	|	4	|	float32	|	3.2	|		|
| 15FFE8 | ?  | 0x84 | ? |  |
|	16006C	|	Speed Multiplier (mostly opponents affected by it)	|	4	|	float32	|	0.95	|	If 0, opponents reach up to 2500km/h easily. High values like 100 can kill them by touch and throw you away	|
| 15FFE8 | ? | 0x48 | ? |  |
|	1600B8	|	Gravity	|	4	|	float32	|	10.0	|		|
|  1600BC | ? | ? | 0x | ? |  |
|	161FB8	|	Vehicle Alphablending	|	4	|	float32	|	1.0	|		|
|   | ? | ? | 0x | ? |  |
|	162510	|	Rescue Rings Color	|		|		|		|		|
|   | ? | ? | 0x | ? |  |
|	163A8C	|	Course background music LUT	|	56?	|	uint8[56?]	|	0x00: No Music	|		|
|   | ? | ? | 0x | ? |  |
|	163AC4	|	Final Lap Music LUT	|	?184	|	?	|		|		|
|   | ? | ? | 0x | ? |  |
|	167890	|	Pilot-to-machine Slots	|	0xa4	|	int[41]	|		|		|
|   | ? | ? | 0x | ? |  |
|	167940	|	Cup Course Slots	|	0x84	|	uint16[0x70]	|	0x0000 - Sand Ocean [Screw Drive]	|	Course IDs as 16-bit values	|
|   | ? | ? | 0x | ? |  |
|	1679C4	|	Course Cup and Cup Assets? Binding	|	0x84	|	uint16[0x70]	|	0x0000 - Sand Ocean [Screw Drive]	|	Course IDs as 16-bit values	|
|   | ? | ? | 0x | ? |  |
|	167A48	|	Unknown Course Cup Binding	|	0x84	|	uint16[0x70]	|	0x0000 - Sand Ocean [Screw Drive]	|	Course IDs as 16-bit values	|
|   | ? | ? | 0x | ? |  |
|	1688CC	|	Course Select Background Image Size	|	4	|	float32	|	Default: 1,3400000333786	|		|
|   | ? | ? | 0x | ? |  |
|	1688FC	|	Cup Emblem Size	|	4	|	float32	|	Default: 0.58	|		|
|   | ? | ? | 0x | ? |  |
|	168900	|	Cup Empblem Boarder Width	|	4	|	float32	|	Default: 0.47	|		|
|	168904	|	Ruby Cup Glow Color	|	4	|	uint8-RGBA	|	0xFF83F200	|	Alpha has no effect	|
|	168908	|	Sapphire Cup Glow Color	|	4	|	uint8-RGBA	|	0x00CAFF00	|	Alpha has no effect	|
|	16890C	|	Emerald Cup Glow Color	|	4	|	uint8-RGBA	|	0x00F0AE00	|	Alpha has no effect	|
|	168910	|	Diamond Cup Glow Color	|	4	|	uint8-RGBA	|	0xF0ECAA00	|	Alpha has no effect	|
|	168914	|	AX Cup Glow Color	|	4	|	uint8-RGBA	|	0xD4189300	|	Alpha has no effect	|
|	168918	|	Venue Name Text Font Size	|	4	|	float32	|	Default: 0.958333	|		|
|	16891C	|	Venue Name Text y-position	|	4	|	float32	|	Default: 79.0	|		|
|	168920	|	Course Name y-Position	|	4	|	float32	|	Default: 105.0	|		|
|	168924	|	Course Icons Beam various positioning, scaling settings Cup 1 - 4	|	0x18	|	int16[12]	|		|		|
|	16893C	|	Course Icons Beam various positioning, scaling settings AX Cup	|	0x18	|	int16[12]	|		|		|
|	168958	|	Course Slot Difficulty Rating	|	0x70	|	int8[112]	|	1 - 6	|	up to 0x18 (24) visible |
| 1689C8  | ?  | 0x22BE8 | ? |  |
|	18B5B0	|	Course Minimap Parameters	|	float[46][7] | 0x508	|		|	 FOV, Pos vec3, look-at vec3 |
| 18BAB8  | ?  | 0x1B44 | ? |  |
|	18D5FC	|	Machine Name List Race Results screen, Time Attack Ranking, Save Ghost Screen, Save Replay Screen, Time Attack Ghost Data List  (Eng, Jpn)	|	0x534	|		|		|		|
| 18DB30 | ?  | 0xBFC | ? |  |
|	18E72C	|	Pilot Name List	Part 1 |	0x17C	|		|		|	0x00-terminated strings. Each entry is right-aligned by a multiple of 4	|
| 18E8A8 | ? | 0x | ? |  |
|	195420	|	Machine Name List (Purpose unknown)	|	0x238	|		|		|	0x00-terminated strings. Each entry is right-aligned by a multiple of 4	|
| 195658 | ? | 0xC | ? |  |
|	195664 |	UI Machine stats	|	7380	|	float[41][45]	|		|	Machine stats are stored in big-endian and are used to produce pickup graphs in the machine setting menu, as well as radar graphs in the shop. Radar graphs are based on a limited number of stats, and will not always be accurate to a machine's performance.	|
| 197338  | ? | 0xC48 | ? |  |
|	197F80	|	Venue Name List	(ENG) |	0xA4	|	|	|	|
|  198024 | ? |  0x58 | ? |  |
|	19807C	|	Venue Name List (JPN)	|	0xD8	|	Shift-Jis|	|	|
| 198154 | ? |  0x370 | ? |  |
|	1984C4	|	Venue Background name list 	|	0xB0	|		|		|		|
| 198574  | ? |  0x160 | ? |  |
|	1986D4	|	Slot Venue Definition LUT	|	112	|		|		|		|
| 198744  | ? |  0x18 | ? |  |
|	19875C	|	Course Name List (English)	|	0x15C	|		|		|		|
|	1988B8	|	Course Name Pointer List	|	0x1BC	|		|		|	Generated during runtime	|
| 198A74  | ? |  8 | ? |  |
| 198A7C  | Course Name List Tags (GER, FRA, SPA, ITA), and Japanese Course name | 0x8d8 | |  |  |
| 199354  | ? |  0xFDC | ? |  |
|	19A330	|	Music File List	|	0xA88	|		|		|		|
| 19ADB8 | ? | 0x184 | ? |  |
| 19AF3C | ? | 0xC4 | ? |  |
|	19B000	|	Pilot Audio File List	|	0x55D0	|		|		|		|
| 1A05D0 | Pilot Audio File Path pointers | 0xECC | int[947] | Generated during runtime |
| 1A149C | SFX File Paths | 0x70 | ? |  |
| 1A150C | ? | 0x4B8 | ? |  |
|	1A19C4	|	Pilot Position|	0x210	|	float32[44][3]	|		|		|
| 1A1BD4 | ? | 0xBFEC | ? |  |
|	1ADBC0	|	AX Mode Course Timer LUT	|	6	|	int8[6]	|	{	0x24, 0x1F, 0x20, 0x21, 0x22, 0x23 } |  |
| 1ADBC6  | ? | 0x10F2 | ? |  |
|	1AECB8	|	Machine Body, Boost, Grip Letter grades	|	0x1EC	|	int[41][3]	|	0 = S, 1 = A, 2 = B, 3 = C, 4 = D, 5 = E	|	Each vehicle has 3 4-byte values (one for each grade)	|
| 1AEEA4  | ? |  0x178C | ? |  |
|	1B0630	|	Banned words list	|	0x3E0	|		|		|
| 1B0A10 | ? |  0xE48 | ? |  |
|	1B1478	|	Custom Machines Special Names	|	0x9A0	|	|		|		|
| 1B1E18 | ? | 0x45C98 | ? |  |
|	1F7AB0	|	Course Name Offsets (English, purpose unknown)	|	0x378	|		|		|
|	1F7E20 |	Course Name Offsets	|	0x14D0	|		|



