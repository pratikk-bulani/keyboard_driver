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

Do check out the error here: https://stackoverflow.com/questions/76011277/keyboard-interrupt-not-working-in-x64-based-machine-on-latest-linux-kernel
