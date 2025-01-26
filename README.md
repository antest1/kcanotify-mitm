# kcanotify mitm addon

A [kcanotify](https://github.com/antest1/kcanotify) addon which uses [mitmproxy](https://mitmproxy.org) to decrypt the TLS/SSL connections and show the decrypted data in the app.

The project is a fork of [PCAPdroid-mitm](https://github.com/emanuele-f/PCAPdroid-mitm) by [Emanuele Faranda](https://github.com/emanuele-f).

The addon uses the open source framework [chaquopy](https://chaquo.com/chaquopy) to bundle and run python modules.  
The native python modules are pre-built and installed from the chaquopy [pip repository](https://chaquo.com/pypi-7.0).


# Prerequisite

Assuming you are building the project on Windows + Android Studio.  
If you want to build on Linux(Ubuntu), check out the instructions in the [original repository](https://github.com/emanuele-f/PCAPdroid-mitm).

1. Set Gradle JDK version to 17 from `Build, Excution, Deployment > Build Tools > Gradle` (e.g. jbr-17) 

2. Install [Python 3.10](https://www.python.org/downloads/release/python-31011/) (required to correctly build with Chaquopy) 