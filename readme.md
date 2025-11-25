# **Salishan Languages Keyboard Support**

**Salishan** is a **keyboard layout for Salishan and neighboring Indigenous languages of the Pacific Northwest**. It extends the standard English keyboard with **dead keys for glottalization, acute accent, tilde, and other diacritics**, enabling efficient typing of **ejective, glottalized, and lateral consonants**, as well as **special vowels** used across multiple Salishan languages. The layout also includes **combining diacritics for rare tonal or phonetic markings**, making it a comprehensive tool for **linguists, language learners, and community members**.

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