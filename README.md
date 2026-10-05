# Ohm's Law Calculator

## Purpose
A small C++ program that reads a voltage (volts) and a resistance (ohms) and prints the current I = V / R.

## Input format
Two numbers separated by whitespace: voltage first, then resistance.

## Build and run
```bash
mkdir -p build
g++ -std=c++17 src/main.cpp -o build/app
./build/app
```
Then type, for example: `12 4`

## Example output
```
Current: 3 A
```

## Testing
Run `bash test.sh` to compile and run the acceptance tests.

## Limitations
- One calculation per run.
- Resistance must be greater than zero.
- Anything after the second number is ignored.
- Non-numeric input prints `Invalid input`.

## Debugging reflection
While logging in to GitHub from WSL, the CLI failed to open a browser automatically. I fixed it by opening https://github.com/login/device manually and entering the one-time code.
