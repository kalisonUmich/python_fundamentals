# python_fundamentals
Example repository containing examples of Python fundamentals


## How I launch my program from the Windows Command Shell (using VS Code)
This assumes you have Python 3.14 installed already. Install it from the Windows Store or from their website at python.org
Thi also assumes you have VS Code installed to code on. You don't need VS Code, but it's free and is more helpful than coding in Notepad.
This also assumes you're in Windows OS but you probably figured that bit out.

It's daunting. I know. Trust me, I'm not writing this for you I'm writing this for me because I know I'll forget how to do it. But you're here anyway. Let's get started:

**Part 1: making and opening the file**
1. Open your file explorer and find the folder you want to create your python file in.
2. Right click and hover over the "new" option. from the popup click "Python source file". now you can name your file. The file will be named "your-file-name.py".
3. Double click the file and select "open in VS Code". now you can write your python file.
4. Great.

**Part 2: running your file**
1. When you want to fun your file, go to the menu on the upper left hand side of your screen and click on "Terminal".
2. Select "New Terminal"
3. Your terminal should open on the homepage of your file directory, starting with PS C:\Users\...
4. Now you need to navigate to your file. the _cd_ command helps you navigate the file directory. If you have your full path available, you can just enter

   cd ~/path/to/your/file.py

including the ~ in the beginning lets you enter multiple folder names at once. if you accidentally enter the wrong folder using _cd_, you can go back to the previous folder by entering

   cd ..

If you need to enter a folder name with spaces in it (like the annoying OneDrive folder name with the spaces) you can get around the terminal's complaints by just surrounding the folder name
in quotes:

   cd "OneDrive - uniquname"

5. Once you're in the folder with your file, you can check to see if you're really there by checking the contents of the folder with the _ls_ command. Just enter

   ls

That's it. If the file shows up, it's in your current directory. Now that you're there, simply use the _py_ command (from the Python you should already have installed) to run your program.
Output will show in your terminal. Make sure you saved your file in VS Code wth ctrl + s before running it.

   py filename.py




