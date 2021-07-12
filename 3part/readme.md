
# for zigbee issues' website:
https://www.silabs.com/community



## host-ncp ota:
https://www.sekorm.com/news/84602495.html

./image-build-windows --create ota-file.ota  --manuf-id 0x1001 --image-type 0x1234 --version 0x0003 --string "ota-file test" --tag-id 0x0000 --tag-file zigbee-ncp-v1.1.0.s37

commander.exe convert custom-bootloader-uart-xmodem-combined.s37 app.hex -o combined\app_combined.hex


## Poll Control:
https://www.silabs.com/community/wireless/zigbee-and-thread/knowledge-base.entry.html/2018/11/29/a_reliable_way_fors-OTah

## How does the polling mechanism work?
https://www.silabs.com/community/wireless/zigbee-and-thread/knowledge-base.entry.html/2014/09/08/how_does_the_polling-sdlT

## EFR32无线通信模块AN310——Zigbee(利用Host升级NCP固件):
https://www.sekorm.com/news/84602495.html


## boot & app firmwares合并
commander.exe convert custom-bootloader-uart-xmodem-combined.s37 app.hex -o combined\app_combined.hex
