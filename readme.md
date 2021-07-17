# Command Line Password Generator

Node.js command line app to generate random passwords

## Usage

Install dependencies

```
npm install
```

Run file

```
node index (options)
```

To create a symlink to run "cli-passgen" from anywhere


## Installation

Install the CLI globally

```sh
npm install -g cli-passgen
```

# Now you can run
cli-passgen (options)

# To remove symlink
```sh
npm uninstall -g cli-passgen
```

# example

```sh
cli-passgen -l 10 -nn
```


## Options

| Short | Long              | Description                     |
| ----- | ----------------- | ------------------------------- |
| -l    | --length <number> | length of password (default: 8) |
| -s    | --save            | save password to passwords.txt  |
| -nn   | --no-numbers      | remove numbers                  |
| -ns   | --no-symbols      | remove symbols                  |
| -h    | --help            | display help for command        |
| -V    | --version         | Show the version                |
