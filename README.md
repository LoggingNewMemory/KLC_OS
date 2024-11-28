![KLC OS Banner](https://github.com/user-attachments/assets/eabf88ec-474a-4e63-99cf-20daafc52f77)

## Source Code? This GSI based on ponces Android 15 AOSP
[日本語](./README_JP.md)

## Build

To get started with building AOSP GSI, you'll need to get familiar with [Git and Repo](https://source.android.com/docs/setup/reference/repo) as well as [How to build a GSI](https://github.com/phhusson/treble_experimentations/wiki/How-to-build-a-GSI%3F)

Note: 
- Pay attention to number 1 - 5
- You need at least 30 GB of RAM to build this
- At least 200 Free storage (HDD or SSD)
- There is a note (Notes.txt) That contains bootanim logo and default wallpaper path, and also system.img path. Hope it helps
- Pay attention to the `KLC_OS/treble_aosp/build.sh` script. I also write something there
- All KLC OS Files are inside KLCStuffs folder

### Steps

1. Create a new working directory for your AOSP build and navigate to it: <br />
`mkdir klc_os; cd klc_os`

2. Clone this repo: <br />
`git clone https://github.com/LoggingNewMemory/KLC_OS -b android15.0`

3. Start the build, Good luck. <br /> 
`bash KLC_OS/treble_aosp/build.sh`

Thanks to:
- [ponces](https://github.com/ponces)
- TrebleDroid Builders Community
- Wahid (Lend me a Server)
