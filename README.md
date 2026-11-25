## Project Files

- `process_creation.c` - Creates a parent and child process using fork()
- `file1.c` - Contains the hello() function
- `file2.c` - Calls the hello() function
- `simple_program.c` - A simple program used to demonstrate shared library dependencies
- `Makefile` - Compiles the programs
- `answers.txt` - Explains the programs, linker and loader
- `LICENSE` - MIT License

## Requirements

- Ubuntu or Linux
- GCC
- Make

Install the required tools:

```bash
sudo apt update
sudo apt install gcc make
```

## Compilation

Open the terminal in the project directory and run:

```bash
make
```

## Running the Programs

Process creation:

```bash
./process_creation
```

Linker example:

```bash
./output_program
```

Loader example:

```bash
./simple_program
ldd simple_program
```

## License

This project uses the MIT License
