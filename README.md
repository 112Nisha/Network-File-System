# Network File System

Our network-based file system offers a set of features enabling the following file operations:

- **Read:** Retrieve content from files.
- **Write:** Create and modify file content.
- **Access Permissions:** Obtain file permission details.
- **Create:** Generate new files.
- **Delete:** Remove files from the system.
- **Copy:** Duplicate files/directories effortlessly.

Access to files is restricted to a predefined list of paths provided by the storage server to the naming server during initialization.

## Setup Instructions

To initialize and operate the file system:

1. **Clone Repository:** Obtain the source code.
2. **Run 'make':** Compile the codebase.
3. **Move Executable:** Place the executable in your desired storage server location.
4. **Define Accessible Paths:** Create a file listing paths for accessibility.
5. **Launch Naming Server:** Execute the naming server (`./nm`).
6. **Start Storage Servers:** Activate storage servers (`./ss`).
7. **Run Clients:** Initiate clients from respective locations.

## Noteworthy Features

- **Concurrent Client Support:** Capable of running multiple clients simultaneously.
- **Access Control:** Ensures clients only access valid and permitted paths.
- **File Handling:** Supports reading files up to 15GB in size.
- **Reliability:** Ensures consistent and reliable functionality.
