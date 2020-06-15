# Python-Pinterest_Bulk_Pin_Uploader
Uploading pins(individual images) from a desktop folder to a specific pinterest board is a tedious process as you have the privilage
only to upload the pins one after the other, this is time consuming and boring process...

what if someone else does that work for you? will that be cool!!...

Using python and selenium this project will be able to upload the files of format(.jpg, .png) to the specific board that you get to select from the available boards in your pinterest profile.

All you have to do to get started is by creating a folder and dump your images after which run this program to upload your pins.

**attention**
Make sure you alter your folder path in the code snippet
![Folder/Path](MetaData/FolderPath.PNG)

After you run your program in the middle of the process you will be promted for your board selection
![BoardSelect](MetaData/BoardSelect.PNG)

After your selection this is gonna be your result
![Final Result](MetaData/Final.gif)

Actually this is version two of the solution and in the first version there will be a file.txt which will hold the board titles instead of getting it from the webelement...

If you want to convert this into a executable file install "pyinstaller package" and in your terminal execute this command 
"pyinstaller --onefile yourScript.py"
