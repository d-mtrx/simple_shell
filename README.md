This is my litle tiny Shell named **simple-shell**.


## Description :triangular_ruler:
The project structure can't have source inside directories, because the only way for compile in this case is `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`

## Installation :floppy_disk:

### Requirements
 - Gcc >= 4.8.4
 - Linux

## Usage :hammer:

supports two modes `interactive` and `non interactive`.

### Basic usage
`./hsh`

### Interactive

 - `./hsh` and then type the commands that you want to execute
 - You can type a command and the prompt appear show again

### Non interactive 

 - `echo "command" | ./hsh`, command is the command that you want to execute
 - Each time that you execute a command, the shell close

## Example :computer:

### Modes

#### Non-interactive
*Command*
```
echo "/bin/ls" | ./hsh
```
*Output*
```
AUTHORS     commands.h     error.c  execute.c  hsh     permissions.c  printers_err.c  README.md  start.c  text.h          utils_text2.c
commands.c  environment.c  error.h  general.h  main.c  printers.c     printers_out.c  shell.h    text.c   tokenization.c  utils_text.c
```
<hr>

#### Interactive
*Command*
```
./hsh
```
Then the prompt appear, so you can type in the command line, and press return
**Ex** - `/bin/ls`

*Output*
```
AUTHORS     commands.h     error.c  execute.c  hsh     permissions.c  printers_err.c  README.md  start.c  text.h          utils_text2.c
commands.c  environment.c  error.h  general.h  main.c  printers.c     printers_out.c  shell.h    text.c   tokenization.c  utils_text.c
```


## Contributors  
Akinyosoye Oluwadotun 
