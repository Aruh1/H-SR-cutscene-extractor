# H-SR-cutscene-extractor(not optimized, but (sometimes) ~works~. feel free to contribute!)

note:*currently working on an overhaul/remaked version!*
---
USM/cg extractor for HSR, made using PyCRIusm
---
**prerequisite:**
python, 
FFMPEG.EXE(Put in Repo)

**Installing**
1. clone this repo
2. download [PyCriUsm](https://github.com/BUnipendix/PyCriUsm)
3. build PyCriUSM using `python setup.py build_ext --inplace`
4. rename the build to decrypt.pyd and replace old decrypt.pyd in USM folder
5. install FFMPEG(only exe)
6. put ffmpeg inside folder
7. use install.bat
8. if someone god knows how managed to not get TabError then good for you, for those who got it, please refer to [this](https://github.com/acezx-programer/H-SR-cutscene-extractor/issues/6#issuecomment-1898752499)
9. Make "output" folder inside the start.bat directory
10. You are good to go!


**Usage**
(Record keys using Iridium-SR for new cutscenes, put in usm/keys.json)
```
install.bat
start.bat
```
Or
```
py main.py [OPTIONS]

options:
  -h, --help         show this help message and exit
  -u <USM>, --usm <USM>  file path of USM file
  -e, --explorer     pick file using File Explorer
  -o, --open         opens video file after merging
```
