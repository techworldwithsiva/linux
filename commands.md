### Commands

Any command in Linux syntax is. Based on the command behaviour we can choose options and inputs.

```
[command-name] [options] [inputs]
```

When we login to Linux server by default we will land into
```
/home/[user-name]
```
In case of centos it is /home/centos.

To get sudo access.

```
sudo su -
```

to change the directory to any other folder.

```
cd [/path/to/folder]
```

#### listing the files.
 
* Just list files and folders.

```
ls
```
* List files and folders in long format
```
ls -l
```
* List files in reverse order.
```
ls -lr
```
* List files in latest time format.
```
ls -lt
```
* List files in reverse time format.
```
ls -ltr
```
* List hidden files. hidden files start with .
```
ls -la
```

#### Cat command

* Just to create empty file
```
touch [file-name]
```
* Create the file and open it to enter text. Enter the text and press ctrl+d to save.
```
cat > [file-name]
```
* Append the text to the file.
```
cat >> [file-name]
```
* Just open the file.
```
cat [file-name]
```

#### remove files
To remove any file.

```
rm [file-name]
```
To remove entire folder. -r means recursive.

```
rm -r [folder-name]
```

#### Copy and move

Copy the file.

```
cp [source] [destination]
```

Copy the folder into another folder, use recursive i.e -r
```
cp [source-folder] [dest-folder] -r
```

Move the file or folder.

```
mv [source-file-or-folder] [destination]
```

Rename the file also same command

```
mv [present-file-name] [new-file-name]
```

#### Others
find text in a file
```
grep [text-to-search] [file-name]
```

top 10 lines in a file.

```
head [file-name]
```

last 10 lines in a files

```
tail [file-name]
```

custom number of lines

```
head -n 5 [file-name]
```

#### File download

To download the file.

```
wget [download-URL]
```

To get the source and show the content in terminal.
```
curl [URL]
```