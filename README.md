# DELL Precision 7520 Big Sur

This repository contains the configurations for Dell Precision 7520, running with Big Sur 11.0.1

## Audio

The configuration allows internal speaker playback but no headphone playback. To enbale headphone playback, follow the guide in this [link](https://www.elitemacx86.com/threads/fix-audio-distortion-when-using-headphones-on-laptops.185/)

To mount `/usr/bin`, boot to Recovery Mode and launch the Termainal.

```bash
mount -uw /
cd /Volumes/<Volume name>
cd ./Users/<user name>/<path to Jack fix>
cp -R /Users/yourusername/Desktop/Jack fix /usr/bin
```

If the above approach does not work, try to follow [this guide](https://osxlatitude.com/forums/topic/11316-how-to-fix-static-noisedistortioncrackling-sound-and-combo-jack-on-laptops/)