```bash
# upload file, reset and run terminal
nodemcu-uploader --port /dev/ttyUSB0 upload app.lua && nodemcu-uploader --port /dev/ttyUSB0 node restart && nodemcu-uploader --port /dev/ttyUSB0 terminal

# build
docker run --rm -ti -v `pwd`:/opt/nodemcu-firmware marcelstoer/nodemcu-build

# flash
esptool.py --port /dev/ttyUSB0 write_flash -fm dio 0x00000 0x00000.bin
esptool.py --port /dev/ttyUSB0 write_flash -fm dio 0x10000 0x10000.bin
```
