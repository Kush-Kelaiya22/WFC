# Wave Function Collapse

This project is an implementation of the Wave Function Collapse algorithm, a constraint-based procedural content generation technique.

## Features

- Procedural generation of patterns
- Configurable parameters
- Visualization of the generation process

## Installation

1. Clone the repository:
	```sh
	git clone https://github.com/yourusername/wave-function-collapse.git
	```
2. Navigate to the project directory:
	```sh
	cd wave-function-collapse
	```
3. Build the project:
	```sh
	make
	```

## Usage

### On Linux

Run the application with the conditions file:
```sh
./wave-function-collapse conditions.txt
```

### On Windows

Run the application with the conditions file:
```sh
wave-function-collapse.exe conditions.txt
```

The output will be generated in a binary file named `output.bin`.

## Makefile Instructions

The provided `Makefile` includes targets for building and cleaning the project.

- To build the project, run:
	```sh
	make
	```

- To clean the build files, run:
	```sh
	make clean
	```
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by the work of Maxim Gumin and his [WaveFunctionCollapse](https://github.com/mxgmn/WaveFunctionCollapse) algorithm.
