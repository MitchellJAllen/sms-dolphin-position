# Super Mario Sunshine Position Data for Dolphin Emulator
The following are the results of using both Cheat Engine and the Dolphin Emulator to find emulated memory addresses for Mario's position in the game Super Mario Sunshine. Spawn positions are also recorded to allow for easy memory searching in case the addresses are incorrect. The provided spawn coordinates are based on Mario falling to the ground and settling before any additional movement occurs. Coordinates are provided as a 64-bit hexadecimal value consisting of Mario's Y and Z coordinates at spawn which can be used to search the emulated memory in Dolphin, and the X coordinate can optionally be used for verification. As a disclaimer, I do own a Nintendo Gamecube console as well as a physical copy of Super Mario Sunshine.

## Table of Contents
* [Information](#information)
* [Delfino Plaza](#delfino-plaza)
* [Delfino Airstrip](#delfino-airstrip)
* [Bianco Hills](#bianco-hills)
* [Ricco Harbor](#ricco-harbor)
* [Gelato Beach](#gelato-beach)
* [Pinna Park](#pinna-park)
* [Sirena Beach](#sirena-beach)
* [Noki Bay](#noki-bay)
* [Pianta Village](#pianta-village)
* [Corona Mountain](#corona-mountain)

## Information
* **Dolphin Emulator Version**: 5.0-12716 (x64)
* **Position Data Type**: 32-bit floating-point number, Big Endian
* **Position Storage**: | **X** - 4 bytes | **Y** - 4 bytes | **Z** - 4 bytes |

## Delfino Plaza
### Spawn Coordinates (Format (X) YZ)
* **Bianco Hills Exit**: (0x00000000) 0x4396000045A41000
* **Dry Slide Level**: (0x44898000) 0x4668D000C6878C00
* **Pinball Level**: (0xC4ED8000) 0xC4FA0000442F0000
* **Lily Pad Level**: (0xC55DE000) 0x4316000046386000
* **Water Slide Level**: (0x00000000) 0x461C400046AFC800
* **Red Coin Level**: (0x451F6000) 0x442F000044480000
### Dolphin Addresses (Y-Coordinate)
* **Main Level**: 0x012F8838
* **Dry Slide Level**: 0x00EB0410
* **Pinball Level**: 0x00ECB570
* **Lily Pad Level**: 0x00E777AC
* **Water Slide Level**: 0x00E1CD00
* **Red Coin Level**: 0x00F01478

## Delfino Airstrip
### Spawn Coordinates (Format (X) YZ)
* **Boat From Delfino Plaza**: (0xC607F0000) 0x42C80000C5A41000
### Dolphin Addresses (Y-Coordinate)
* **Main Level**: 0x0105A954

## Bianco Hills
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment**: (0xC6034000) 0x45366E63469AB000
* **Petey Fight (Episode 2)**: (0x3FEEFDF4) 0x4040000044610000
* **Secret Level (Episode 3)**: (0xC5BEA000) 0x455480004347FFFE
* **Secret Level (Episode 6)**: (0x00000000) 0x45FA0000464D7800
### Dolphin Addresses (Y-Coordinate)
* **Episode 1**: 0x01382840
* **Episode 2**:
  * **Starting Segment**: 0x013219A0
  * **Petey Fight**: 0x00F0B0EC
* **Episode 3**:
  * **Starting Segment**: 0x0129ECC0
  * **Secret Level**: 0x00F32E80
* **Episode 4**: 0x01309260
* **Episode 5**: 0x013A9500
* **Episode 6**:
  * **Starting Segment**: 0x0122AFA0
  * **Secret Level**: 0x00EBE154
* **Episode 7**: 0x0125EB80
* **Episode 8**: 0x01288BE4

## Ricco Harbor
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment**: (0xC6516000) 0x439600034528C000
* **Blooper Race (Episode 2)**: (0x463B8000) 0x41200000C5898000
* **Secret Level (Episode 4)**: (0xC5E10000) 0x458340002E3F0000
### Dolphin Addresses (Y-Coordinate)
* **Episode 1**: 0x013BC98C
* **Episode 2**:
  * **Starting Segment**: 0x013BCD24
  * **Blooper Race**: 0x00FBEFB8
* **Episode 3**: 0x0133274C
* **Episode 4**:
  * **Starting Segment**: 0x012ED064
  * **Secret Level**: 0x00E7ECC0
* **Episode 5**: 0x013B75CC
* **Episode 6**: 0x012E868C
* **Episode 7**: 0x012F144C
* **Episode 8**: 0x0137C7E4

## Gelato Beach
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment (Episodes 1-4, 6)**: (0x46273000) 0x42480000C5610000
* **Starting Segment (Episodes 5, 7, 8)**: (0x46273000) 0x42480000C55AC000
* **Secret Level (Episode 1)**: (0x???) 0x???
* **Secret Level (Episode 4)**: (0x???) 0x???
### Dolphin Addresses (Y-Coordinate)
* **Episode 1**:
  * **Starting Segment**: 0x013921A8
  * **Secret Level**: 0x???
* **Episode 2**: 0x013AE8F0
* **Episode 3**: 0x01414E50
* **Episode 4**:
  * **Starting Segment**: 0x0135C970
  * **Secret Level**: 0x???
* **Episode 5**: 0x0138AA08
* **Episode 6**: 0x013821C0
* **Episode 7**: 0x013A3C28
* **Episode 8**: 0x01398B50

## Pinna Park
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment (Episode 1)**: (0xC55AC000) 0xC19D908446228000
* **Starting Segment (Episodes 2-8)**: (0xC55AC000) 0xC1BD13CB46234800
* **Amusement Park (Episode 1)**: (0xC5610000) 0x43C8000044610000
* **Amusement Park (Episodes 3, 5-8)**: (0xC555C000) 0x43C80000447F0000
* **Secret Level (Episode 2)**: (0x???) 0x???
* **Secret Level (Episode 6)**: (0x???) 0x???
### Dolphin Addresses (Y-Coordinate)
* **Episode 1**:
  * **Starting Segment**: 0x013B8968
  * **Amusement Park**: 0x012D8B6C
* **Episode 2**:
  * **Starting Segment**: 0x0138774C
  * **Secret Level**: 0x???
* **Episode 3**:
  * **Starting Segment**: 0x013A582C
  * **Amusement Park**: 0x012D5BB4
* **Episode 4**: 0x014143D4
* **Episode 5**:
  * **Starting Segment**: 0x013E9D8C
  * **Amusement Park**: 0x012D5ED4
* **Episode 6**:
  * **Starting Segment**: 0x013E9D8C _(same as Episode 5)_
  * **Amusement Park**: 0x012EC290
  * **Secret Level**: 0x???
* **Episode 7**:
  * **Starting Segment**: 0x013E9D8C _(same as Episode 5)_
  * **Amusement Park**: 0x012EE2B4
* **Episode 8**:
  * **Starting Segment**: 0x013E9D8C _(same as Episode 5)_
  * **Amusement Park**: 0x012DF634

## Sirena Beach
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment**: (0xC57DC07E) 0x4248000045B8D3E7
* **Hotel Delfino (Episodes 2-5, 7, 8)**: (0x00000000) 0x8000000045188000
* **Secret Level (Episode 2)**: (0x???) 0x???
* **Secret Level (Episode 4)**: (0x???) 0x???
* **The Casino (Episodes 4, 5)**: (0x3EADE658) 0x80000000C572F164
* **Boo Fight (Episode 5)**: (0x???) 0x???
### Dolphin Addresses (Y-Coordinate)
* **Episode 1**: 0x012BEED4
* **Episode 2**:
  * **Starting Segment**: 0x011F3DC4
  * **Hotel Delfino**: 0x010FE130
  * **Secret Level**: 0x???
* **Episode 3**:
  * **Starting Segment**: 0x012137E4
  * **Hotel Delfino**: 0x0138BD6C
* **Episode 4**:
  * **Starting Segment**: 0x012138E4
  * **Hotel Delfino**: 0x0136B6D0
  * **The Casino**: 0x01158488
  * **Secret Level**: 0x???
* **Episode 5**:
  * **Starting Segment**: 0x01213BA4
  * **Hotel Delfino**: 0x0136B6D0 _(same as Episode 4)_
  * **The Casino**: 0x00FF2EE8
  * **Boo Fight**: 0x???
* **Episode 6**: 0x011D4474
* **Episode 7**:
  * **Starting Segment**: 0x011E5384
  * **Hotel Delfino**: 0x0122FDC8
* **Episode 8**:
  * **Starting Segment**: 0x01215CA4
  * **Hotel Delfino**: 0x01381188

## Noki Bay
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment**: (0xC5FB4000) 0x431DFBE6C511A000
* **Bottle Coins (Episode 3)**: (0x???) 0x???
* **Eel Fight (Episode 4)**: (0x???) 0x???
* **Secret Level (Episode 6)**: (0x???) 0x???
* **Fish Coins (Episode 8)**: (0x???) 0x???
### Dolphin Addresses (Y-Coordinate)
* **Episode 1**: 0x014686E8
* **Episode 2**: 0x01417AE4
* **Episode 3**:
  * **Starting Segment**: 0x01275E34
  * **Bottle Coins**: 0x???
* **Episode 4**:
  * **Starting Segment**: 0x012E7584
  * **Eel Fight**: 0x???
* **Episode 5**: 0x012FD204
* **Episode 6**:
  * **Starting Segment**: 0x0130DDE4
  * **Secret Level**: 0x???
* **Episode 7**: 0x012F6CA4
* **Episode 8**:
  * **Starting Segment**: 0x01349A64
  * **Fish Coins**: 0x???

## Pianta Village
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment (Episodes 1-4, 6-8)**: (0x00000000) 0xC4169708468EF800
* **Starting Segment (Episode 5)**: (0x00000000) 0xC3C8000046947000
* **Secret Level**: (0x???) 0x???
### Dolphin Addresses (Y-Coordinate)
* **Episode 1**: 0x0132A6B8
* **Episode 2**: 0x01249674
* **Episode 3**: 0x0139F5D0
* **Episode 4**: 0x012A26B4
* **Episode 5**:
  * **Starting Segment**: 0x012BFF74
  * **Secret Level**: 0x???
* **Episode 6**: 0x01328DB4
* **Episode 7**: 0x013808D8
* **Episode 8**: 0x01251584

## Corona Mountain
### Spawn Coordinates (Format (X) YZ)
* **Starting Segment**: (0x42C80000) 0x4418800046B54000
### Dolphin Addresses (Y-Coordinate)
* **Starting Segment**: 0x01061A64
