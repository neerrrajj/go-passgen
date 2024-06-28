# Password Generator Tool

This CLI tool, written in Go, generates random passwords with customizable options. Users can specify the password length and choose to include digits and special characters.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/neerrrajj/go-passgen.git
    cd password-generator-tool
    ```

2. Install dependencies:
    ```sh
    go get github.com/spf13/cobra
    ```

## Usage

Run the application with the desired options:
```sh
go run main.go generate -l 12 -d -s
```

Command options:
- `-l, --length`: Length of the generated password (default is 8).
- `-d, --digits`: Include digits in the generated password.
- `-s, --special-chars`: Include special characters in the generated password.

Output:

```bash
generating password...
aB3$dFg7HiJkLmN9
```