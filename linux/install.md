## Linux :: Debian

### Install the package

```sh
sudo dpkg -i ./linux/salishan-keyboard_1.0_all.deb
```

### Remove the package

```sh
sudo dpkg -r salishan-keyboard
```

This will safely remove the layout files and the entries added to your system.

---

### Build the Debian Package

From the `salishan` folder:

```sh
dpkg-deb --build ./linux/deb ./linux
```