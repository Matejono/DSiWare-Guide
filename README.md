# DSiWare-install
Way, how to install DSiWare into your DSi (including Flipnote Studio and Web Browser)

## You will need:

- Files from this page.

- Your DSiWare in `.cia` format (if you don´t have one, MarioCube is possibility)

- One empty SD card

- `Python` installed on your PC (get it there: https://www.python.org/downloads/)

- One .bin file from your DSi SD card (you can copy some software from your DSi)

- Patience ;D

Note, if you have more than 200 free blocks, you´re fine. If not, watch out the size! You can brick your DSi, if you install DSiWare to full memory.
Note: I´m not responsible for wrong process and bricking your DSi. It won´t be my fault if you don´t properly read my instructions and brick your DSi.

## Instructions

1. Extract all folders from `zip archive`.

2. Copy files from `camerapithax` folder to root of your empty SD Card.

4. Drag your `.bin` file to ConsoleID Extract and run console_id.py. You will get txt file. Copy that file to root of the SD card.

5. Now you will need `DSiWare`. If you don´t have that, you can download it from `MarioCube Repository`. Drag one game to ctrtool folder, rename your game to `dsiware.cia`. Run `extract.bat`. You will get two files. Delete that with 0 kb and rename other one to `00000000.app`. If windows ask you to change file type, then press Yes.

6. Now go to webpage: https://www.3dbrew.org/wiki/3DS_DSiWare_Titles and find your title `TWL-TitleID` with coresponding `region`. Double check your region!!! Copy the `TWL-TitleID` and find it in `tmds` folder. Copy to `ctrtool` folder

7. Then rename your tmd to `title.tmd` and drag with `.app` file to SD card to data in `Game Folder`.

8. Insert your SD to DSi. Launch `DSi Camera` and go to SD Card/Album. If it asks you to make nand backup, do it.

9. Press `X` to mount directly your nand (if successful, text will be red), `navigate` to `Game folder/data` and Press `A` on `title.tmd`. If numbers on app file are matching, you will be asked to allow install, press `A` and wait. If not matching, You will be prompted with error that certain `.app file` is missing. note the name of `8-number .app file` that appears to be missing, `unmount` nand pressing `select` and turn off your DSi.

10. Put your SD card back to PC and rename `00000000.app` with the combination you noted. Repeat steps `8 and 9`.

11. When successfuly installed, `unmount NAND` by pressing `select` and then `A`. DSi will turn off. Boot it up and you will see present. Open it up.

12. Go to `Settings, Data magement`. `Copy` your game `to SD card` and `delete one in NAND`. `Copy from SD card back`. `This is fix, so you won´t be prompted with message, that NAND is full`.


Note: Games tested and `work with Wiimmfi and KaeruWFC`. Flipnote studio tested and work with `IPGflip and Sudomemo`.
