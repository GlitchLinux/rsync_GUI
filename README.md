# rsync_GUI

A simple Bash script that provides a graphical user interface (GUI) using Zenity for selecting source and destination paths for an `rsync` operation.

## Features
- Uses Zenity to prompt for source and destination paths.
- Displays a confirmation dialog before executing `rsync`.
- Shows progress during the `rsync` operation.
- Notifies the user upon successful completion or failure.

## Prerequisites & Usage
Ensure the following dependencies are installed:
- `zenity`
- `rsync`

On Debian/Ubuntu-based systems, install dependencies, clone the repository, make the script executable, and run it using:
```sh
sudo apt update && sudo apt install zenity rsync
git clone https://github.com/GlitchLinux/rsync_GUI.git
cd rsync_GUI
chmod +x rsync_GUI.sh
./rsync_GUI.sh
```

Follow the Zenity prompts to select the source and destination directories, confirm the operation, and wait for the process to complete.

## License
This project is licensed under the MIT License.

## Author
[GlitchLinux](https://github.com/GlitchLinux)

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

