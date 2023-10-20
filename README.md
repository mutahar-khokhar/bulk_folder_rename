# Bulk Folder Rename

Automate the process of renaming multiple folders in a directory using a list of names from a text file.

## Features

- **Custom Directory Path**: Set the directory where folders need to be renamed.
- **Input Text File**: Provide a text file with the new folder names.
- **Efficient Renaming**: The script matches names from the file to folders and renames them.
- **Error Handling**: Checks for matching counts of folders and names to prevent errors.

## Getting Started

1. Clone or download this repository to your local machine.

2. Ensure you have Python installed.

3. Create a text file, "what-file.txt", in the same directory as the script. Add one name per line for the folders you want to rename.

4. Edit the `directory_path` variable in the script to specify the directory where your folders are located.

5. Run the script.

```python
python bulk_folder_rename.py
