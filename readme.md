```sh
sudo cp -f 30-touchpad.conf /etc/X11/xorg.conf.d/30-touchpad.conf
cat /etc/X11/xorg.conf.d/30-touchpad.conf

xinput list
xinput list-props 25
xinput set-prop 14 306 1
```