# 0x02. Shell, I/O Redirections and filters

---

## Learning Objectives

### Shell, I/O Redirection
- What the commands 'head', 'tail', 'find', 'wc', 'sort', 'uniq', 'grep', 'tr' do
- How to redirect standard output to a file
- How to get standard input from a file instead of the keyboard
- How to send the output from one program to the input of another program
- How to combine commands and filters with redirections

### Special Characters
- Understand what special characters are and what to do with them

### Other Man Pages
- How to display a line of text
- How to concatenate files and print on the standard input
- How to reverse a string
- How to remove sections from each line of files
- What is the '/etc/passwd' file and what is its format
- What is the '/etc/shadow' file and what is its format

---

## Tasks

### 0.Hello World
*Write a script that prints "Hello, World", followed by a new line to the standard output.*

### 1.Confused smiley
*Write a script that displays a confused smiley '"(Ôo)''.*

### 2.Let's display a file
*Display the content of the '/etc/passwd' file.*

### 3.What about 2?
*Display the content of the '/etc/passwd' and '/etc/hosts' files.*

### 4.Last lines of a file
*Display the last 10 lines of '/etc/passwd'.*

### 5.I'd prefer the first ones actually
*Display the first 10 lines of '/etc/password'.*

### 6. Line #2
*Write a script that displays the third line of the file 'iacta'.*

### 7.It is a good file that cuts iron without making a noise
*Write a shell script that creates a file named '\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)' containing the text 'Best School' ending by a new line.*

### 8.Save current state of directory
*Write a script that writes into the file 'ls_cwd_content' the result of the command 'ls -la'. If the file 'ls_cwd_content' already exists, it should be overwritten. If the file 'ls_cwd_content' does not exist, create it.*

### 9.Duplicate last line
*Write a script that duplicates the last line of the file 'iacta'.*

### 10. No more javascript
*Write a script that deletes all the regular files (not the directories) with a '.js' extension that are present in the current directory and all its subfolders.*

### 11. Don't just count your directories, make your directories count
*Write a script that counts the number of directories and sub-directories in the current directory.*

### 12.What's new
*Create a script that displays the 10 newest files in the current directory.*

### 13.Being unique is better than being perfect
*Createa script that takes a list of words as input and prints only words that appear exactly once.*
- Input format: one line, one word
- Output format: one line, one word
- Words should be sorted

### 14.It must be in that file
*Display lines containing the pattern "root" from the file* '/etc/passwd'

### 15.Count that word
*Display the number of lines that contain the pattern "bin" in the file* '/etc/passwd'

### 16.What's next?
*Display lines containing the pattern "root" and 3 lines after them in the file* '/etc/passwd'

### 17.I hate bins
*Display all the lines in the file '/etc/passwd' that do not contain the pattern "bin".*

### 18.Letters only please
*Display all lines of the file '/etc/ssh/sshd_config' starting with a letter. Include capital letters as well.*

### 19.A to Z
*Replace all characters 'a' and 'c' from input to 'z' and 'e' respectively.*

### 20.Without C, you would live in hiago
*Create a script that removes all letters 'c' and 'C' from input.*

### 21.esreveR
*Write a script that reverses its input.*

### 22.DJ Cut Killer
*Write a script that displays all users and their home directories, sorted by users.*

