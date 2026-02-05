# Arduino CLI Installation and Path Configuration

The following instructions guide you through the installation of Arduino CLI and the configuration of the PATH environment variable on Windows, macOS, and Ubuntu.

## 1. Installation

### Windows
1. Download the Arduino CLI executable:
   - Visit the [Arduino CLI GitHub Releases](https://github.com/arduino/arduino-cli/releases).
   - Download the latest `.zip` file for Windows.
2. Extract the `.zip` file to a directory of your choice (e.g., C:\ArduinoCLI).


### macOS
1. Open the Terminal.
2. Install Arduino CLI using Homebrew:  
   ```brew install arduino-cli```

### Ubuntu
1. Open the Terminal.
2. Download the Arduino CLI executable:
   ```
   curl -fsSL https://raw.githubusercontent.com/arduino/arduino-cli/master/install.sh | sh
   ```
3. Verify the installation by running:
   ```
   arduino-cli version
   ```

## 2. Configure the PATH Environment Variable

### Windows 11
1. Open the Start Menu and search for "Edit the system environment variables."
2. Select "Edit the system environment variables".
3. In the "Advanced" tab, click "Environment Variables".
4. Under User Variables, find and select the Path variable, then click Edit.
5. Add the path to the Arduino CLI executable (e.g., C:\ArduinoCLI).
6. Click OK to save changes and restart any open command prompt windows.
7. Open the Terminal and verify the configuration by running"
```
arduino-cli version
```



### macOS
If you install Arduino CLI via Homebrew, there is no need to configure the PATH environment variable. You can verify the installation by following these steps:
1. Open the Terminal.
2. Run `arduino-cli version`

### Ubuntu
If you install Arduino CLI via Homebrew, there is no need to configure the PATH environment variable. You can verify the installation by following these steps:
1. Open the Terminal.
2. Run `arduino-cli version`


### Video Tutorial
- [Firmware Upload Video](https://www.youtube.com/watch?v=Nx1yT0BBrlE) 