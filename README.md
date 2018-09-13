<p align="center">
  <a href="https://github.com/konkor/vtt2srt"><img src="https://img.shields.io/github/license/konkor/vtt2srt.svg" alt="GPLv3 License"></a>
  <a href="https://github.com/konkor/vtt2srt"><img src="https://img.shields.io/github/stars/konkor/vtt2srt.svg?style=social&label=Star&style=flat-square" alt="Stars"></a>
</p>

# [VTT to SRT Converter](https://github.com/konkor/vtt2srt)


VTT2SRT is an GPLv3-licensed open source project focused on desktop users. It's an independent project with its ongoing development made possible entirely thanks to the support.

Please, consider to support the project and make it better!

**VTT2SRT** helps to convert VTT (Web Video Text Tracks) to SRT format.

## How-to use
1. Create `FILE.srt`
```
vtt2srt FILE.VTT
```
2. Create `FILE1.srt, FILE2.srt, FILEN.srt`
```
vtt2srt FILE1.VTT FILE2.VTT FILEN.VTT
```
3. Specify output (single file only)
```
vtt2srt FILE.VTT FILENAME.SRT
```
3. Using pipes
```
cat  FILE.VTT | vtt2srt > FILENAME.SRT
```
3. Using stdin for input and FILENAME for output
```
cat  FILE.VTT | vtt2srt FILENAME.SRT
```

## Contributions
* Report [a bug](https://github.com/konkor/vtt2srt/issues).
* Test it on your favorite Linux distribution.
* Contribute with an idea, graphical content, translation or code [an issue](https://github.com/konkor/vtt2srt/issues).
* Make donation to the project.

## Donations
Please, consider to support the author seriously at least temporary or one time. It's an independent open software project. It means there is no any organization or company behind it to support it except generous users. The time for the development, supporting, debugging, testing is not less then for any other project. Otherwise the project could have only spontaneous updates and supporting until it just die. **All donations is for all open-source projects of the autor.**

 * [Become a backer or sponsor on Patreon](https://www.patreon.com/konkor)
 * [PayPal EURO](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WVAS5RXRMYVC4)
 * [PayPal USD](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HGAFMMMQ9MQJ2)
 * Contact to the author [here](https://konkor.github.io/index.html#contact)

_Behind the development for the Linux Desktop are ordinary people who spend a lot of time and their own resources to make the Linux Desktop better. Thank you for your contributions!_


## Installation
### Dependencies
* gjs
* gir1.2-glib-2.0

Linux installation:
```
make
sudo make install
```

### Sources and binary packages
* [GitHub master branch](https://github.com/konkor/vtt2srt/archive/master.zip)
