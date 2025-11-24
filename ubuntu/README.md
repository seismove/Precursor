# **Seismove Software**

This page contains the Seismove software installation for Ubuntu. Below are the details on how to install and use the software.

---

## **Ubuntu Installation**

The firmware uploader software requires the Arduino CLI as a dependency. For installation instructions, please refer to [arduino_cli installation](../firmware/arduino_cli.md).

### **Latest Version**
The latest versions of the software are available at the links below:

[**Download Seismove Precursor Client v3 for SM-P**](https://drive.google.com/file/d/1L5-E6VR8bPiFIKJGoReQ17lFhFOFNcty/view?usp=drive_link) (**SM-P-004**)

[**Download Seismove Precursor Client v2.1 for SM-P**](https://drive.google.com/file/d/116nsnRJIjpLF0QwRIEJBdZ8S0YjxtgOj/view?usp=drive_link) (**SM-P-001**, **SM-P-002**, **SM-P-003**)

[**Download Seismove Precursor Client v2.1 for SM-P1**](https://drive.google.com/file/d/1GNjNS3VP-dXRfQyzm-JNcbQwCE6ZbYSk/view?usp=drive_link)

[**Download Seismove Firmware Upload**](https://drive.google.com/file/d/1UQDqaFqVX24UbVUUWW4tEsIY_WX4w3uw/view?usp=drive_link)

1. Click the link to download the `.tar.gz` file.
2. Open a terminal and navigate to the directory containing the downloaded `.tar.gz` file.
3. Extract the .tar.gz file:
```
tar -xzvf SeismoveInstaller.tar.gz
```

4. Navigate to the extracted folder
5. Ensure the executable files have the proper permissions: 
```
chmod +x Seismove_client 
chmod +x Seismove_firmware_uploader
```

6. Launch the applications by double clicking or running the following commands: 
```
./Seismove_client # To launch Seismove Client 
./Seismove_firmware_uploader # To launch Seismove Firmware Uploader
```

### **Archived Versions**
Previous versions will be made available in the future.

---

## **Features**
- **Seismove Client**:
  - Provides an intuitive interface for monitoring and control of your Seismove devices.
- **Seismove Firmware Uploader**:
  - Enables seamless firmware updates for your devices.

---

## **System Requirements**
- Ubuntu 18.04 or later
- At least 500 MB of free disk space

---

## **Usage Instructions**
1. Install the software as per the instructions above.
2. Launch the required application:
   - **Seismove Client**: For monitoring and control.
   - **Seismove Firmware Uploader**: For firmware updates.
3. Follow the on-screen instructions for each application's functionality.

---

## **Issues**
If you encounter any problems or bugs while using the software, we encourage you to report them. Please follow these steps to submit an issue:

1. Go to the **Issues** tab of this repository.
2. Click **New Issue**.
3. Provide a clear and descriptive title.
4. In the issue description, include:
   - Steps to reproduce the issue.
   - Expected behavior.
   - Actual behavior.
   - Any relevant screenshots or logs.

We appreciate your feedback and will work to address issues as soon as possible!