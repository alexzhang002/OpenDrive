# opendrive

A cross platfrom application for managing files and folders in cloud storage.

## Getting Started

You can download the latest version from application store with the following links(Only need pay 1.99$ support us):

Or you can build the application from source code:

```bash
git clone https://github.com/OpenCloudDrive/OpenDrive.git
cd OpenDrive
```

- macOS

```
go build -tags nosqlite -ldflags="-w -s" --buildmode=c-shared -o macos/Frameworks/libgopeed.dylib github.com/rclone/rclone/librclone
flutter build macos
```

## Support Platform

- [x] Android
- [x] iOS
- [x] macOS
- [x] Windows
- [x] Linux

## Features

Support for multiple cloud storage providers:

- [x] Google Drive
- [x] Dropbox
- [x] OneDrive
