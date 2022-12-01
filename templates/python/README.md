# Python AoC Template

## Requirements

* Python 3.5+

## Instructions

* Run `make prepare`
* Go to [adventofcode.com](adventofcode.com) and paste your input to `input.txt`
* (Optional): Search for the simple example stated in the puzzle description and paste it to `simple.txt`

## Commands

| Command   | Description |
|---        |---          |
| `make part1`  | Runs your solution for part 1 of today's puzzle   |
| `make part1_simple`  | Runs the solution for part 1 with the simple input with optional debug logs   |
| `make part1`  | Runs your solution for part 2 of today's puzzle   |
| `make part1_simple`  | Runs the solution for part 2 with the simple input with optional debug logs |
| `make prepare`  | Prepares the working directory. |
| `make clean`    | Resets the working directory.   |

## Information

The Python scripts in this directory feature a `debug` option and a `debug()` function.
To print out debug information, make sure not to use the `print` function, as it destroys the clarity of the output.
Debug output by default will be printed out to stdout for the `make partX_simple` targets.
