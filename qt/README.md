[aqt-install](https://aqtinstall.readthedocs.io/en/latest/getting_started.html)
========

```shell
aqt list-qt windows desktop --arch 5.10.0
    win32_mingw73 win32_msvc2017 win64_mingw73 win64_msvc2015_64 win64_msvc2017_64

aqt list-qt windows desktop --archives 5.10.0 gcc_64
    icu qt3d qtbase qtcanvas3d qtconnectivity qtdeclarative qtgamepad qtgraphicaleffects qtimageformats qtlocation qtmultimedia qtquickcontrols qtquickcontrols2 qtscxml qtsensors qtserialbus qtserialport qtspeech qtsvg qttools qttranslations qtwebchannel qtwebsockets qtwebview qtx11extras qtxmlpatterns

# aqt.exe install-qt --outputdir ${base_path} ${host} ${type} ${target} ${arch} ${host_flag} -m qtbase qtmultimedia
aqt.exe install-qt --outputdir ./qt-5.10.0-msvc2017_64 windows desktop 5.10.0 win64_msvc2017_64 --archives qtbase qtmultimedia qttools qttranslations
```
