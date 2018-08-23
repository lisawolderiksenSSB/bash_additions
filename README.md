# bash_additions
Additions for bash - aliases and functions which can come in handy

## Installation
Clone this repo into your home directory using HTTPS...
```bash
cd ~
git clone https://github.com/statisticsnorway/bash_additions.git
```
...or using SSH
```bash
cd ~
git clone git@github.com:statisticsnorway/bash_additions.git
```

Include the bash_additions file in your `~/.bash_profile` so the aliases and functions are available in *new* terminals/shell windows by adding the following line to `~/.bash_profile`:
```bash
source ~/bash_additions/bash_additions
```

To use the aliases and functions in the *current* terminal/shell, run the same command directly in the terminal/shell:
```bash
source ~/bash_additions/bash_additions
```

## How to contribute 
Please feel free to add your own bash aliases, functions etc. if you think they could be of use to others. 

Consider adding your contributions in a new file, if they are "specialised" in some way. It might make sense to have a separate "git_additions" or "google_cloud_additions" or similar, containing aliases and functions for those use cases. 

Anyone in the statisticsnorway GitHub organization can push to this repo. So go ahead - just do it! :) (Please follow the normal procedures using branches and pull requests, though.) 
