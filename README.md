📁 File and Directory Management Tool

This is a simple yet powerful Python script that allows you to perform common file and directory operations such as reading, writing, renaming, moving, deleting, compressing, and listing files and directories. 

---
How to install

    pip install geraci
---

✅ Features 

    Read file contents
    Overwrite or append content to a file
    Create new files or directories
    Rename, move, or delete files
    Compress files into ZIP archives
    Decompress ZIP archives
    List files in a directory
     

All operations are logged with timestamps for debugging and tracking purposes. 
 
🔧 Requirements 

    Python 3.x
    Standard libraries used:
    • os
    • logging
    • shutil
    • zipfile

No external dependencies required. 
 
📋 How to Use 

    EXAMPLE 1

    from geraci import Core

    Core.read_file("file_name.txt")

    EXAMPLE 2
    from geraci.core import rename_file

    rename_file("old_name.txt", "new_name.csv")
     

 
📌 Example Operations 
___
• Read a file

  → File name/path
___
• Overwrite a file

  → File name, then choose "Write" or "Load"
___
• Append to a file

  → File name, then choose "Write" or "Load"
___
• Create a new file

  → Optional file name
___
• Rename a file

  → Old and new file names
___
• Move a file

  → File name and destination path
___
• Delete a file
  → File name/path
___
• Create a directory

  → Path for the new directory
___
• List files in a directory

  → Directory path
___
• Compress a file into ZIP

  → File name and ZIP archive name
___
• Decompress a ZIP archive

  → ZIP file name and extraction path
___

⚠️ Validation & Error Handling 

    Validates file names to ensure they contain an extension.
    Handles common errors like missing files, permission issues, etc.
    Returns clear error messages using warning (⚠️) or error (❌) icons.
     

 
📂 Sample Usage Scenarios 
Create and Write to a File 
text
 
 
1
2
4 → rubrica.txt
2 → rubrica.txt → Write → Mario Rossi, 35 old
 
 
Append Content from Another File 
text
 
 
1
3 → rubrica.txt → Load → new_contacts.txt
 
 
Compress a File 
text
 
 
1
10 → rubrica.txt → contacts.zip
 
 
 
📄 License 

This project is open source under the MIT License . 
 
🧑‍💻 Author 

Developed as a general-purpose file utility tool in Python. 