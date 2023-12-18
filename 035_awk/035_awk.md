# awk

### `Used to`: Scans a file line by line, Splits each input line into fields, Compares input line/fields to pattern, Performs action(s) on matched lines

### `Syntax` :- awk options 'selection \_criteria {action}' input-file > output-file

> Ex: dpkg -l | awk '/ii/ {print $2" "$3}' | sort > installed_packages.txt

- List all the packages of the current system, grab the full version from the output, Sort it and store it in a file
