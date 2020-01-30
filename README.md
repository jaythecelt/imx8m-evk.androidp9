# imx8m-evk.androidp9
Tools and images to flash Android on to the NXP IMX8M-EVKB kit.  This repo just collects the needed files all in one place.

See Android_Quick_Start_Guide_P9.pdf section 4.0 for instructions on how to flash the IMX8M-EVKB eMMC (Andorid or Linux)

This repo also includes uuu.exe (Windows) and uuu files, version 1.2.19 from https://github.com/NXPmicro/mfgtools/releases/tag/uuu_1.2.91  (see "Assests").  The doc says the scripts were verified to run with this version, so that's why I used 1.2.19 instead of the latest.

IMX8_evk_getting_Started.pdf is the little flyer included with the dev kit.

All other files were downloaded from NXP, specifically at https://community.nxp.com/external-link.jspa?url=https%3A%2F%2Fwww.nxp.com%2Fwebapp%2FDownload%3FcolCode%3DP9.0.0_2.0.0_GA_DEMO_8MQ%26appType%3Dlicense

Also see this announcment on the community site: https://community.nxp.com/docs/DOC-343278


I added some debug statements to uuu_imx_android_flash.bat to help with debugging the script, but otherwise there are no modifications.
