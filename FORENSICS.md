# Forensics
In a CTF context, Forensics involves any challenge which requires to examine and process a hidden piece of information out of static data files. It includes the following sub-categories:
- File Formats
- Image Analysis
- Steganography
- Audio Analysis

## File Formats
The first and the fore-most thing to check is the file format of the given file. You can use the `file` command to do the same, which uses a ***magic*** file that contains all the patterns to recognize a file type and doesn't care about the ***extension*** of the file.
```console
$ file <file_name>
```
In this example, the file `challenge.jpeg` seems to be a `JPEG` file but is actually a `PNG` file.<br><br>
![](assets/img/file.png)