# Contribution guidelines

If you like to improve the `next` script, the templates or add new technologies, please fork this repository and open a pull request with your changes and a brief summary of your changes.

New templates should meet these requirements:

* Include a README.md file with similar content as in the current templates. They should include:
  * system requirements
  * instructions on how to work with that project
  * a list of commands to run both parts from the command line.
* Provide a debug flag, and maybe a function, so that debug outputs can be toggled on or off.
* Use a flag to specify the file input to prevent duplicate code.
* Provide a way to set up the working environment (like `make preview` in the [python template](./templates/python/)).
* Include a `.vscode/` folder with recommended extensions for [VSCode](https://code.visualstudio.com/). It also can include workspace settings, to set up a formatter or similar.
* Add potential files and folders to `.gitignore`. Maybe with the help of [gitignore.io](https://gitignore.io)
