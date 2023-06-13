# mlkhs
USDX High scores plugin for the My Little Karaoke Project

UWebSDK.pas from the UltraStar-Deluxe/USDX codebase: `src/webSDK/UWebSDK.pas`

## Making your plugin
You will want to download the relevant OpenSSL libraries.
You can get these from https://indy.fulgan.com/SSL/ (but other sources exist).

When running `test.exe`, you'll want `libeay32.dll` and `ssleay32.dll` in the same directory.

## Distributing your plugin
The easiest way is to provide your users with a zip folder that has the following structure:
```
libeay32.dll
ssleay32.dll
webs/
  mlkhs.dll
```
and then instruct them to unzip it in the directory where UltraStar Deluxe is installed.
This is the directory where `ultrastardx.exe` is located.
