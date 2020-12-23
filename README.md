<h1 align="center">
	<img src="firefox.png" alt="Firefox" height=200 width=200 align="middle">
	Firefox AppImage
</h1>

Mozilla Firefox Stable, Beta and Nightly (unofficial) AppImages by GitHub Actions Continuous Integration

## Get Started

Download the latest release from

| Stable | Beta | Nightly | ESR | Developer Edition |
| ------- | --------- | --------| ------ | --------- |
| <img src="firefox.png" height=100> | <img src="https://mozilla.org/media/protocol/img/logos/firefox/browser/beta/logo-lg.160afbe8e73f.png" height=100>  | <img src="https://upload.wikimedia.org/wikipedia/commons/b/b4/Firefox_Nightly_logo%2C_2019.svg" height=100> | <img src="firefox.png" height=100> | <img src="firefox.png" height=100> | 
| [Download](https://github.com/srevinsaju/Firefox-AppImage/releases/tag/firefox) | [Download](https://github.com/srevinsaju/Firefox-AppImage/releases/tag/firefox-beta) | [Download](https://github.com/srevinsaju/Firefox-AppImage/releases/tag/firefox-nightly) | [Download](https://github.com/srevinsaju/Firefox-AppImage/releases/tag/firefox-esr-next) | [Download](https://github.com/srevinsaju/Firefox-AppImage/releases/tag/firefox-devedition) |



### Executing
#### File Manager
Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
the `+x` permissisions. So, right click > Properties > Allow Execution

#### Terminal 
```bash
./Firefox-*.AppImage
```
```bash
chmod +x Firefox-*.AppImage
./Firefox-*.AppImage
```

In case, if FUSE support libraries are not installed on the host system, it is 
still possible to run the AppImage

```bash
./Firefox-*.AppImage --appimage-extract
cd squashfs-root
./AppRun
```

## License
"Mozilla Firefox" is licensed under the [Mozilla Public License 2.0  (MPL 2.0)](https://en.wikipedia.org/wiki/Mozilla_Public_License)
The official source code of the Mozilla Firefox is available at links provided 
* https://developer.mozilla.org/en-US/docs/Mozilla/Tech/Viewing_and_searching_Mozilla_source_code_online
* https://hg.mozilla.org/mozilla-central/

"GH Continuous Integration" is licensed under the MIT License. 
