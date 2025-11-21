# CSE233 Assignment 2

This project has small C programs for the OS course

They show:

- how a process is created
- how to link code from more than one C file
- how a simple loader works


## Build

Use `make` to compile the programs.

```bash
make
```

This will create these executable files:

- `process_creation`
- `output_program`
- `simple_program`

To delete the compiled files and start fresh, run:

```bash
make clean
```

## Run

After you build the programs, run each one like this:

```bash
./process_creation
./output_program
./simple_program
```

To see which shared libraries `simple_program` uses, run:

```bash
ldd simple_program
```

## License

This project uses the MIT License (see the `LICENSE` file).
