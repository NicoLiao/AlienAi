<p align=center>
<img target = "banner" src="https://raw.githubusercontent.com/NicoLiao/AlienAi/main/1660395285063.png">
</p>

<p align=center>
<a target="badge" href="https://github.com/NicoLiao/AlienAi" title="python version"><img src="https://img.shields.io/badge/python-v3.9.6-blue"></a>
<a target="badge" href="https://github.com/NicoLiao/AlienAi" title="windows badge"><img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" width=85/></a>  
</p>

>This is a game where you have to shoot down aliens and not get touched. You get 50 scores if you killed an alien and enter next level if you cleared all the aliens
>However, you have an AI to play for you this time. This AI will learn from past experiences and do better each time.

# Install
## Release 

## Download source code
In order to use AlienAi, make sure that you have python 3.9.6 and python packages as below:
pygame 2.0.1
pyinstaller 4.10
torch 1.12.0
matplotlib 3.4.3
ipython 8.4.0
```
$ git clone https://github.com/NicoLiao/AlienAi
```
## Usage
### Visual Studio Code
Download VSCode https://code.visualstudio.com/
Download python https://www.python.org/
After installing VScode and Python, download the extension in VSCode as follow:
* python
* python for vscode
* code runner

Done it and Run code

### Build exe
Using terminal and pyinstaller to build exe
```
$ pyinstaller -F agent.py -c
```
