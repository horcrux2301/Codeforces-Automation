## AFCP

#### AFCP is a Competitive Programming Contests Automation Package for text editor Atom.

[![Installs!](https://img.shields.io/apm/dm/afcp.svg?style=flat-square)](https://atom.io/packages/afcp)
[![Package version!](https://img.shields.io/apm/v/afcp.svg?style=flat-square)](https://atom.io/packages/afcp)
[![GitHub stars](https://img.shields.io/github/stars/horcrux2301/AFCP.svg)](https://github.com/horcrux2301/AFCP/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/horcrux2301/AFCP.svg)](https://github.com/horcrux2301/AFCP/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/horcrux2301/AFCP.svg)](https://github.com/horcrux2301/AFCP/stargazers)
[![GitHub license](https://img.shields.io/github/license/horcrux2301/AFCP.svg)](https://github.com/horcrux2301/AFCP)



Sites Supported | Yes
------------ | -------------
Codechef | :white_check_mark:
Codeforces | :white_check_mark:
Atcoder | :white_check_mark:

`Note:- The package has been fairly tested for MacOS and Linux. However Windows users might face some issues. Please open one in the repo if you do.`.

[Never used atom for competing? Read this](#packages)

## Installation

Install package either by running `apm install afcp` from the terminal or by searching in the Install menu from Atom.

You will also need to install the following to use the package properly.

Linux -

1. [Install gcc](https://gist.github.com/application2000/73fd6f4bf1be6600a2cf9f56315a2d91)
2. Install coreutils. (Generally it is installed already.)

MacOS-

1. Install gcc. This can be done by installing Xcode or Command Line Developer Tools.
2. Install coreutils. This can be done via homebrew. `brew install coreutils`.

Windows -

1. Install MinGW.
2. Install coreutils


## Usage

**Add the directory locations**
---

Add directory locations for each site i.e where you want the folder for the problems to be created.

![Image](https://i.imgur.com/x66KloC.png)

An example location can look like this:- `/Users/harshkhajuria/Desktop/TEST/` .

**Important. Don't forget to add a `/`(for MacOS and Linux) or '\' (for Windows) at the end of the location.**

You can drag and drop the folder into terminal to get the paths

![Drag and drop](https://i.imgur.com/24oNmfa.gif)

`coreutils` is used to make sure that your code doesn't goes into an infinite loop. The time limit right now is `5 seconds` which can be edited from the setting menu.

**To fetch the problems and testcases**
---

![Image](https://i.imgur.com/HRwTUOT.png)

Press `alt+control+k` to open the pane. Check the site radio button and put the contest code into the input field. Press `Fetch Data` .

A folder will be created for each of the problems with their test cases in the directory that you specify in the settings menu.


#### Examples for Code of Contests.

Site | Link | Code
------------ | ------------- | -------------
Codechef | https://www.codechef.com/COOK94A | COOK94A
Codechef | https://www.codechef.com/MAY18B | MAY18B
Codeforces | http://codeforces.com/contest/354 | 354
Codeforces | http://codeforces.com/contest/490 | 490
Atcoder | https://arc097.contest.atcoder.jp/ | arc097
Atcoder | https://agc024.contest.atcoder.jp/ | agc024


*In order to close the pane press again `ctrl+alt+k`*

**To compile and create output files**
---

Press `alt+control+c` to compile. One output file will be generated for each and every file that starts with `input` in the folder where `.cpp` file is.

In order to create your own test cases create a input*.txt file in the same directory of the problem replacing * with a integer.
Corresponding output file can be generated by pressing `control+alt+c` again.

# Packages

Install the following packages for using atom to code in C/C++. To install them go to `Install` in `Preferences` and search them by typing their name.

1. [autocomplete-clang](https://atom.io/packages/autocomplete-clang) - Autocompletion of C/C++ code.
2. [gpp-compiler](https://atom.io/packages/gpp-compiler) - Compile C/C++ code from within Atom.
3. [linter](https://atom.io/packages/linter) - Base Linter.
4. [linter-ui-default](https://atom.io/packages/linter-ui-default) - Default UI for the linter package.
5. [linter-clang](https://atom.io/packages/linter-clang) - Linter for C/C++ files.
