# Advent of Code Starter

This repository can be used as a template for your [Advent of Code](https://adventofcode.com) puzzle solutions.

The key to this repo is the `next` script and the `templates` folder. With that script, you can create a quick project for each day's puzzle fast.
Simply execute the script like that for generating the next day's folder in a random technology.

```bash
./next
```

However, you can manipulate the behavior of the script with the following parameters (you could also use `./next -h` for a quick overview of options).

| Flag  | Description   | Example   |
| ---   | ---           | ---       |
| `-y`, `--year`    | Specifies the year, for which AoC event you want to create the next project. By default, the current year will be picked.  | `./next -y=2021`   |
| `-t`, `--technology`  | Specifies the language, in which the project should be generated. By default, a random technology will be picked. For available technologies, see [Supported Technologies](#supported-technologies).   | `./next -t=python`    |

## Supported Technologies

The following technologies can be used for generating projects:

* Python
* TypeScript (with [Deno](https://deno.land/))

## Blacklist

There might be technologies you are not familiar with, or which you don't want to use. Therefore, you can list every technology (must match the folder name in `./templates`) in the
`blacklist.txt` file (one technology per line). With that, these technologies will not get included in the random generation. However, specifying a technology with the `-t` flag will ignore the blacklist.


## Use this template

To use this repository, make sure **NOT** to fork this repository, but to use the „Use this template“ button and create your own repository.

## Contributing

_see [CONTRIBUTING](CONTRIBUTING.md)_
