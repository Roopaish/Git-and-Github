# Git & Github - The Practical Guide (by Academind)

## Version Management/Control

- Control and Tracking of code or any file changes over time
- Saving progress as you go
- To have backup files to get back to if any problems/bugs arises
- Avoid writing multiple side copies of files for every draft
- In version management, its easier to jump back and forth to any draft in single file

## Git & Github

- Git is Version Control System, manages code history, tracks changes and is a local tool.
- Github is Largest Development Platform, Cloud Hosting & Collaboration Provider, Git Repository(Git Project) Hosting.

## Text Based Computer Interaction (git-bash on windows)

- Time Saving, start servers, download & install tools, run code, execute files, working with git.
- Where our project is

```bash
pwd
```

- Change Directory

```bash
# cd to home directory / inside user profile directory
cd ~

# cd to root directory / top level
cd /

# go back to up one hierarchy level from current level
cd ..

# cd to specific folder (use tab as you type some of the first letters of folder or file)
cd Git/

# Use \ before spaces in file or folder name
cd Git\ \&\ Github\ -\ The\ Practical\ Guide/

# cd to absolute path
cd cd /w/Documents/Git\ \&\ Github\ -\ The\ Practical\ Guide/

# clear the terminal
clear
```

- Create and Delete files and folder

```bash
# create folders
mkdir folder_name

# create file/s
touch index.html
touch styles.css app.js

# delete file/s
rm index.html
rm styles.css app.js

# delete folder/directory which is empty
rmdir folder_name

ls -s # list files along with its size
ls -l # list files with additional data like creator, date, time
ls -ls # list files with additional info and size

# delete non-empty folder
rm -r folder_name
```

- Copy and move

```bash
# copy file
cp source_path target_path

# copy all files from the folder
# without / the folder will also get copied
cp -r source_path/ target_path/

# move file
mv source_path target_path/

# move folder
mv source_path target_path/

# rename existing files
mv styles.css style.css
```

- For Command Prompt (cmd)

```bash
# change local disk
D:

# list files and folder in current directory
dir

# clear terminal
cls

# create file
echo content of the file > test.txt

# see content of file
type test.txt

# delete file and folder
del test.txt
rmdir folder_name
```
