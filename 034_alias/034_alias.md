# alias

### Shell aliases are a simple way to create new commands or to wrap existing commands with code of your own. They somewhat overlap with shell functions, which are however more versatile and should therefore often be preferred.

### Create an alias

> alias word='command'

- Ex: alias now='date'
- Ex: print_things = 'echo "foo" && echo "bar"'

> Remove an alias

- unalias {alias_name}

> Bypass alias

- command {command name}

* suppose you've alias as ls = 'ls --color=auto' and you want to bypass this then write 'command ls'
