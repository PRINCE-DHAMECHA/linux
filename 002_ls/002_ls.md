# ls

### `Used to` : list directory contents

### `Syntax` :- ls [OPTION]... [FILE]...

> Option-1 : "{directory name}"

- **Ex:** ls download

  Shows all files of download folder of current working directory, if exists, Error otherwise.

> Option-2 : {wildcards}

- **Ex:** ls Documents/\*.html

  List down all html files of Documents folder

> Option-3 : "-l"

- long listing format.

  filetype.owner.group.everybodyElse symbolicLinks ownerName groupName size date filename

  filetype: "-" means file, "d" means directory

> Option-4 : "-a"

- Shows hidden files as well.

> Option-5 : "-S"

- Sort by size (bigger to smaller).

> Option-6 : {save output content}

- **Ex:** ls -lS > out.txt

  Save output of "ls -lS" into out.txt

> Option-7 : "-r"

- When used with the -r option the sort order is reversed.

      Explore more option by "man ls"...
