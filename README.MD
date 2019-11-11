# Download Android Emulator Database

Script used to bring files from within the android emulator to your local machine.
Previously this script was used to export Expo.io application files. But now it is adapted to download the files of any application that is parameterized through the package.

## Requirements
- OS: MAC or LINUX
- ADB installed and working perfectly as envroinment variable
- Emulator installed and working perfectly


## Installation


```bash
git clone https://github.com/iredhd/download-emulator-db.git download-emulator-db
cd dowload-emulator-db
```

## Usage
- Run your application normally inside your emulator.
- Run the following command:
```bash
./downloadDB app.package directory/to/download/ destination/directory/
```
- Accept the backup on your emulator (**DO NOT SET A PASSWORD**)
- Wait while the magic occurs

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
