# imx8m-evk.androidp9
## Tools and images to flash an Android P9 image to the NXP IMX8M-EVKB kit.  

The purpose of this repo is to collect the needed files and useful docs all in one place.

### Add a folder and unzip Android P9 files
Contruct a folder on Windows 10, download and unzip the files at  https://community.nxp.com/external-link.jspa?url=https%3A%2F%2Fwww.nxp.com%2Fwebapp%2FDownload%3FcolCode%3DP9.0.0_2.0.0_GA_DEMO_8MQ%26appType%3Dlicense then add/overwrite with the files in this repo in the same folder.

Also see this announcement on the community site: https://community.nxp.com/docs/DOC-343278

### Download this repository
Copy these files to the same folder you created.

In this repository:
- Android_Quick_Start_Guide_P9.pdf
- IMX8_evk_getting_Started.pdf ... the little flyer included with the dev kit.
- uuu.exe and uuu downloaded from https://github.com/NXPmicro/mfgtools/releases/tag/uuu_1.2.91.  The doc says the scripts were verified to run with this version, so that's why I used 1.2.19 instead of the latest.

### Follow the Docs
See Android_Quick_Start_Guide_P9.pdf section 4.0 for instructions on how to flash the IMX8M-EVKB eMMC (Andorid or Linux)
When running on Windows, be sure to run the command line as administrator.
