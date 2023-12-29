# apple-display-with-windows
This provides the software needed to adjust brightness on an Apple Studio Display on Windows.

### How to install
- Open Powershell
- Run `Start-Process msiexec.exe -verb runAs -Args "/i C:\Users\YourUserName\Downloads\Apple\BootCamp.msi`, adjusting the path if needed (e.g. replace `YourUserName`)
  - `Start-Process` is used to elevate permissions to be able to install the package. Alternatively, open Powershell as admin and `msiexec /i C:\Users\YourUserName\Downloads\Apple\BootCamp.msi`
- After the installation is complete, run `C:\Windows\System32\AppleControlPanel.exe`
- In the Apple Control Panel interface, the `Display` tab and adjust the brightness
![Boot Camp Control Panel](https://github.com/abcp23/apple-display-with-windows/assets/155123336/a0d3fb53-20e2-4db0-ac34-acfbad118ed2)
