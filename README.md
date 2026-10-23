# Seat of Power: Windows builds

Compiled builds of Seat of Power only (no source). The source is in the private repository
[warbladebg/seat-of-power](https://github.com/warbladebg/seat-of-power).

## Running it

1. Install [Git LFS](https://git-lfs.com) once (`git lfs install`). `SeatOfPower.exe` and `data/map/heightmap.png` are
   stored with LFS, so without it they arrive as small pointer files and the game won't start.
2. Clone the repository. It is about 2.4 GB:
   `git clone https://github.com/warbladebg/seat-of-power-builds.git`
3. Run `SeatOfPower.exe`. Windows 10/11 x64; the .NET runtime is included.

Settings, saves and decision logs go to the `userdata\` folder next to the exe. Git ignores that folder, so a
`git pull` for a newer build keeps your saves.

All rights reserved. See LICENSE.txt, ATTRIBUTION.md and licenses/.
