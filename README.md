# PAPK (Ported Android Package Kit)

PAPK is an innovative app that allows running Android APK files on **Windows, Linux, and macOS** without traditional emulators.  
It uses the **AOSP Android Runtime**, so it runs the APK directly rather than emulating it.

> ⚠️ Warning: Some APKs may not run because they use non-AOSP APIs.

## Features

- Cross-platform: Windows, Linux, macOS  
- APK installation and analysis interface  
- Lightweight and fast  
- Modular backend, frontend, and Lua structure  
- User APKs and runtime files are managed locally  
- Log and error reporting support

## Installation & Running

### Linux / macOS

```bash
# Go to the packaged folder
cd Linux/PAPK-linux-x64

# Check the files
ls

# Give execute permission
chmod +x PAPK

# Run the application
./PAPK
