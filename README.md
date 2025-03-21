# DSATester
edit 2025-02-21T13-44-00  
edit 2025-02-21T13-59-00  
edit 2025-02-21T14-09-30  
edit 2025-02-21T14-15-30  
edit 2025-03-17T10-37-50  
edit 2025-03-17T11-04-10  
edit 2025-03-17T11-40-50  
edit 2025-03-17T15-20-00  
github edit 2025-03-18T14-06-00  
github edit 2025-03-18T14-55-00  
github edit 2025-03-18T15-27-00  
github edit 2025-03-19T13-33-00
balh  
## Introduction
A small program to generate test results for DSA 4.1. Entries in the hero xml file (created by Helden-Software) are compared with dice rolls which can be generated or typed in. 
Additionally, any number of dice sums can be calculated by typing the desired dice roll (e.g. "3d20" or "5d6+4"). The result can then be saved in a csv file.

Current supported entries which can be tested include:
* Eigenschaften
* Talente
* Zauber
* Kampftalente

Project progress can be viewed at: https://trello.com/b/TuCnQlQi/dsatester

## Technologies
* helden-software 5.5.3-1 from Archlinux User Repository (for character creation)
* Python3.8.5
* pyinstaller (to create executable)

## Launch
1. Place your xml file(s) in the "hero_files" folder
2. Change the values in "config.txt" based on your preferences
3. Launch "main.py" or "main.exe"

## Usage
### Command Line Interface
![CLI version](./images/DSATester-cli-cut.gif)

### Graphical User Interface
![GUI version](./images/DSATester-gui-cut.gif)

## Diagrams
### Code structure
![Code structure](./images/structure.png)
### Flowchart
![Flowchart](./images/flowchart.png)
