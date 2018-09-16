npm install exceljs
Node.js 8.9.3, Chromium 61.0.3163.100, and Electron 2.0.6.

wget -nc https://dl.winehq.org/wine-builds/Release.key
sudo apt-key add Release.key
sudo apt-add-repository https://dl.winehq.org/wine-builds/ubuntu/
sudo apt-get update
sudo apt-get install --install-recommends winehq-stable
sudo npm install electron-packager -g
electron-packager ./ electric_power_company --platform=win32 --icon=logo.icns
electron-packager /home/bsfx/electron-quick-start/ electric_power_company --platform=windows
electron-packager . electric_power_company --overwrite --asar=true --platform=win32 --arch=ia32 --icon=logo.icns --prune=true --out=release-builds
