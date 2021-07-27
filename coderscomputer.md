# <center> <b>Text Editor </b> </center>

A text editor is a piece of software that you download and install on your computer. A text editor allows you to open, view, and edit plain text files. Unlike word processors, text editors do not add formatting to text, instead focusing on editing functions for plain text.

## <center> <b>Features to Look for in a Text Editor</b> </center>

* Easy to use and navigate (similar to a good word processor)
* Find and replace feature (so you can change a single word in the whole file with a few clicks)
* Cut, Copy, Paste (again, similar to word processors)
* Code Completion
* Syntax highlighting (unlike your word processor, this makes it easier to read code and pick up any errors)
* Customizable appearance (such as modifying font size, color schemes, etc., of your editor which optimizes your work zone)
* Extensibility – (provide some plugin mechanism, or is scriptable, so a programmer can customize the editor with additional features)

# <center> <b>Using Terminal Commands</b> </center>

### 1. **pwd**
   The pwd command stands for print working directory. It is one of the most basic and frequently used commands in Linux. When invoked the command prints the complete path of the current working directory.  Use code often to remind yourself where you are!

### 2. **ls**
The command is short for list. ls stands for “list files” and will list all the files in your current directory. 

### 3. **cd**
This command means to change directory. This will change the directory that you're currently working with in the Terminal in order to execute other commands on a different directory, view the contents of a different directory or open a file in a different directory. 
  * **Tip** If you ever lose your place and which directory you're in, type pwd (print working directory) and press Return to echo the current path.
  
# <center> **Paths** </center>

There are 2 types of paths **absolute** and **relative**. 

1. **Absolute paths** specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )
* We can say that an absolute path is a complete path from start of actual file system from / directory.
>             1. lisatarran@CO1234: ls /home/listarran/Documents
>             2. file1.txt file2.txt file3.txt



2. <b>Relative paths</b> specify a location (file or directory) in relation to where we currently are in the system.
   * **They will not begin with a slash.**                                      
>                       1. lisatarran@CO1234: ls Documents
>                       2. file1.txt file2.txt file3.txtfile1.txt file2.txt file3.txt </form>

