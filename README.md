# Widevine Dumper

Frida script to dump L3 CDM

## Usage

* Run `pip install -r requirements.txt` or `pip3` to install the dependencies
* Enable USB debugging
* Start Frida server on the device
* Run `dump_keys.py`
* Play DRM protected content

## Notes

* Google made changes in OEMCrypto library and broke the script. Further investigation is needed to make it work on Android 11+
* To temporarily disable L1 to use L3 use a Magisk module called [liboemcrypto-disabler](https://github.com/umylive/liboemcrypto-disabler)
* Fork of [wvdumper/dumper](https://github.com/wvdumper/dumper)
