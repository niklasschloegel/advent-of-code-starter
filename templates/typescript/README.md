# Python AoC Template

## Requirements

- [Deno](https://deno.land/manual@v1.28.2/getting_started/installation)
  Installation

## Instructions

- Run `deno task prepare`
- Go to [adventofcode.com](adventofcode.com) and paste your input to `input.txt`
- (Optional): Search for the simple example stated in the puzzle description and
  paste it to `simple.txt`

## Commands

| Command                  | Description                                                                 |
| ------------------------ | --------------------------------------------------------------------------- |
| `deno task part1`        | Runs your solution for part 1 of today's puzzle                             |
| `deno task part1_simple` | Runs the solution for part 1 with the simple input with optional debug logs |
| `deno task part1`        | Runs your solution for part 2 of today's puzzle                             |
| `deno task part1_simple` | Runs the solution for part 2 with the simple input with optional debug logs |
| `deno task prepare`      | Prepares the working directory.                                             |
| `deno task clean`        | Resets the working directory.                                               |

## Information

The TS modules in this directory feature a `debug` option and a `debug()`
function. To print out debug information, make sure not to use the `console.log`
function, as it destroys the clarity of the output. Debug output by default will
be printed out to stdout for the `deno task partX_simple` targets.
