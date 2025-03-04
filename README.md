# Automated File Sorter

An automated file sorter using Python that organizes files in a specified directory into categorized folders based on their extensions.

## Features

- **File Sorting:** Automatically sorts files into three categories:
  - **Excel files** (`.xlsx`)
  - **Image files** (`.jpg`, `.png`)
  - **Text files** (`.txt`)
- **Dynamic Folder Creation:** Automatically creates destination folders if they do not exist.
- **User-Friendly:** A simple and easy-to-use script.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ayaelsaoudi1/Automated-File-Sorter-in-File-Explorer-using-Python.git
   ```

2. **Modify the Path:**
   Open the script and change the `path` variable to point to the directory you want to organize:
   ```python
   path = r"C:/path/to/your/directory/"
   ```

3. **Customize File Extensions:**
   You can add any type of file extension to the code to sort additional file types.  
   Simply modify the conditions in the script to include your desired extensions.  
   For example:
   ```python
   elif file.endswith(".your_extension"):
       shutil.move(path + file, path + 'your_folder/' + file)
   ```
