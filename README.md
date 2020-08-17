# TunerPro (and other) Engine Tune Repository

This is an unofficial fork of the LS_Based_Engine_Repository created by BoredTruckOwner
https://github.com/BoredTruckOwner/LS_Based_Engine_Repository


Please note that a significant portion of the BIN files from from Gearhead-EFI
http://www.gearhead-efi.com/


The following repository is designed to house various engine management configuration files. The current data held is more for Tuner Pro (XDF and BIN) however this repository need not only work for that software.

Any and all files in this repository are very much use at your own risk. The validity of these files cannot be verified.


To controbute to this repository consider creating a branch or fork in Github and adding modifying the files you wish to work on.  If you have new bin files either add them to the appropriate section, or create an issue and attach the file.

The owner of this respositor take no credit in the generation of any of these files, that has been done by the hardwork of many many others. If you upload a file please identify yourself in the metadata card, if you found the file online please credit the author if known.


Repository structure is defined below.

- ->Manufacture
- - -> ECM Generation
- - - -> Hardware Information (repo for HW specifics)/Software Information (tuning files)
- - - - -> (software) Applicable ECU section
- - - - - -> Folder for each different OSID.
- - - - - - -> XDF/ADX stored at top level; Each BIN is given a folder named "OSID_VIN"
- - - - - - - -> Within each VIN folder is the BIN file and a readme metacard with searchable vehicle details (BIN details pulled from "PCMBINBuilder" (joukoy https://github.com/joukoy/PCMBinBuilder) and VIN details from https://vpic.nhtsa.dot.gov/decoder/ 


Various Tuning efforts

https://pcmhacking.net/forums/viewtopic.php?f=7&t=1396

https://pcmhacking.net/

http://www.gearhead-efi.com/

https://ls1tech.com/forums/pcm-diagnostics-tuning-7/

http://nefariousmotorsports.com/forum/?fbclid=IwAR3fW6ZktqkqJFC_8xJjSZDQHnQGZFtcdG0pk9EEpt0IPQlIp0ua8hdSu78

https://m44.fandom.com/wiki/M44_Wiki

https://www.discotd5.com/
