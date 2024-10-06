
# Command Line Interface (CLI) Essentials

## Redirecting Input and Output

### Output Redirection
- By default, output is sent to the screen.
- Using `>` is to save output into a file.
- Using `>>` is to add output to an existing file or create a new file.
- The `cat` command is display the contents of text files.

### Input Redirection
- The standard input is taken from the keyboard.
- Use `<` to read input from a file instead.
- Input and output redirection can be combined in a single command.

## Connecting Commands with Pipelines
- The `|` allows chaining commands.
- Ex.
  ```bash
  command_first | command_second | command_third
  ```

## File Permissions
- Use `chmod` to modify file permissions.

### Superuser Access
- The superuser can execute system-wide commands.
- Use `sudo` before entering commands 


## Writing Shell Scripts
- You can write and run custom shell scripts


### Downloading Files from the Internet
- **Wget** is using download files from the web.
  ```bash
  wget [URL]
  ```

- **Curl** can transfer data across the web.
  ```bash
  curl -O [URL]
  ```

### Searching Text with Grep
- **Grep** find specific text file.
  - Some useful options:
    - `-i` is ignore case
    - `-v` is invert the match
    - `-r` is recursive search 



## Advanced Input/Output and Pipelines

### Redirecting Output
- Redirect the output of a command in a file with `>`.
- Use `>>` to append output to a file, do not overwriting.

### Using Pipelines to Link Commands
- Multiple commands can be used together using `|`:
  ```bash
  ls | grep ".txt"
  ```


