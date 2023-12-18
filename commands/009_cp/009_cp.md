# cp

### `Used to` : copy

### `Syntax` :- cp [OPTION]... SOURCE... Destination

> Ex: cp file1.txt file2.txt

- copy file1.txt to file2.txt (it will create new file)

> Ex: cp file1.txt Docs/file2.txt

- copy file1.txt to file2.txt inside Docs directory

> Option-1 : "-i"

- Ask before override

> Option-2 : "-R"

- copy directories recursively

* Ex: cp -R dir1 dir2

- Create dir2 if not exist, copy content of dir1 into dir2
- Transfer dir1 into dir2, if dir2 exist

> Option-3 : "-v"

- Information of what's going on
