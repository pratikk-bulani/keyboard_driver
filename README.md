# keyboard_driver

Works only for Ubuntu 18.04 and its corresponding kernel version. Will not work in newer kernel version.

Steps to execute:
```
make
sudo insmod hello.ko
# Check the output in another terminal using the command: dmesg -w
# Type something using keyboard
# Check the output using the command: sudo cat /sys/kernel/key_logger
sudo rmmod hello
```
