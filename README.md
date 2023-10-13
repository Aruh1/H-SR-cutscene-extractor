# H-SR-cutscene-extractor(not optimized, but works. feel free to contribute!)
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
8. You are good to go!


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
