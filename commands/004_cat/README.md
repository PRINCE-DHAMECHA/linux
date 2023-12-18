# cat

### `Used to` : Concatenates or displays files

### `Syntax` :- cat [OPTION]... [FILE]...

> Ex: cat

- Echo shell (Echo whatever you write)
- ctr+d to exit

> Ex: cat file1.txt

- print content of file1.txt

> Ex: cat file1.txt file2.txt

- print content of file1.txt followed by file2.txt

> Option-1 : "-b"

- Add line numbers to non-blank line

> Option-2 : "-n"

- Add line number to all lines

> Option-3 : "-s"

- Add squeeze blank line to one blank line ( will not change actual file )

> Option-4 : "-E"

- Add '$' to end of each line

* concatenate gzipped files

> Ex: cat file1.gz file2.gz > combined.gz
