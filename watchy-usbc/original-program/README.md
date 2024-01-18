Here is the stock program dumped from the esp32 like that
```
esptool.py --port /dev/ttyACM1 --baud 921600 read_flash 0 0x400000 backup.bin
```
can be flashed using:
```
esptool.py --chip esp32 --port /dev/ttyACM1 --baud 921600 --before default_reset --after hard_reset write_flash -z --flash_mode dio --flash_freq 80m --flash_size detect 0x0 backup.bin
```
Here is an awesome video on this topic: https://youtu.be/2GwzbBn7uRw

\+ Reset the esp:
```
esptool.py --after hard_reset chip_id
```
