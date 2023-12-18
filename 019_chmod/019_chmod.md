# chmod

### `Used to` : change permissions

> Ex: chmod o+x file

- give others permission of execute

> Ex: chmod og-wx file

- remove groups and others permission of write and execute

> Ex: chmod ug=wx file

- give permission of u and g to -wx

> Ex: chmod a=wx file

- give permission of all to -wx

> Octal permissions

### user group others

> chmod 777

- rwx rwx rwx
- 111 111 111
- 421 421 421
- =7 =7 =7

> chmod 530

- r-x -wx ---
- 101 011 000
- 421 421 421
- =5 =3 =0
