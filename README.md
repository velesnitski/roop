## Original repo with all info, kudos to the Author(s)
https://github.com/s0md3v/roop

## How do I install it?
> Note: The instructions may or may not work for you. Use google or look through issues people have created here to solve your problems.

Typical install: 'pip install -r requirements.txt'

Other options for parent version:
please check original install instructions on parent repository: https://github.com/s0md3v/roop/wiki/1.-Installation

Download [this file](https://drive.google.com/file/d/1jbDUGrADco9A1MutWjO6d_1dwizh9w9P/view?usp=sharing) and keep it in **roop** directory. [Mirror #1](https://drive.google.com/file/d/1eu60OrRtn4WhKrzM4mQv4F3rIuyUXqfl/view?usp=drive_link), [Mirror #2](https://1drv.ms/u/s!AsHA3Xbnj6uAgxhb_tmQ7egHACOR?e=CPoThO)


## How do I use it?
> Note: When you run this program for the first time, it will download some models ~300MB in size.

Executing `python run.py` command will launch this window:
![gui-demo](gui-demo.png)


Working command line arguments are given below:

```
options:
  
  --gpu                 use gpu

```

For now recommendation is to use: 'python run.py' without gpu options since the code not commited yet.

## Fixes and Recommendations for M1+(ARM) Macs (May 2023)
Python 3.10

python-tk@3.10

openssl@1.1