# python_led

rpi_ws281x/python/examples $ sudo python test.py
can work

cd
mkdir wifi-firmware
cd wifi-firmware
wget https://github.com/RPi-Distro/firmware-nonfree/raw/master/brcm/brcmfmac43430-sdio.bin
wget https://github.com/RPi-Distro/firmware-nonfree/raw/master/brcm/brcmfmac43430-sdio.txt
sudo cp *sdio* /lib/firmware/brcm/
sudo reboot
