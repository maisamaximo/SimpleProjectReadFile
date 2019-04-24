# Simple Project Read File

Suppose there are text files whose contents need to be read and displayed on the screen. The file format is as follows:

```
1
16/12/2005 20:00:00
John Howard
58    158.20      10/11/1980  FC3E3444D   8
63    200.14      06/04/1991  ABC123EFG   7
20    314.74      02/02/2010  DAC942FFF   4
```

The first line contains a list of the columns in the file.
In the case above, the number 1 indicates that the structure of the document should be as follows:
- First column: int
- Second column: float
- Third column: data
- Fourth column: String
- Fifth column: int
That way, files with the number 2 See other settings for columns.

The second line contains the data and the time that the file was generated.
The third line contains the name of the user who generated the
archive.
The content of the file is written from the fourth line.

Create a design that allows the contents of the files to be read and displayed on the screen. At that time, the information must
only be displayed on the screen.

## How run this project

1. Clone the project
2. Open it on your favorite IDE
3. Run the file 'Main.java'

```In code we trust ❤ ```
