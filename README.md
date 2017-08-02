# bm - Bookmark your daily basis command line

Save all your daily basis command lines with bm easily
## Quick Start
1. Clone the repo `git clone https://github.com/AlkindiX/bm.git`
2. Copy `bm` file to one of your favorite locations. I prefer `/usr/bin` for system wide and `/home/<Your name>/.local/bin/` for your own
3. `chmod +x /path/to/bm` to enable excution 

## Requirements
1. Python version 3 and up

## Command Line Usage
| Argument            | Description                                                                   | Example                                   |
| ------------------- | ------------------------------------                                          | ----------------------------------------- |
| `bm b KEY ARGS,...` | Create a new bookmark with arguments                                          | `bm b ssh_myserver ssh root@192.168.0.5`  |
| `bm KEY`            | Launch your favorite code                                                     | `bm ssh_myserver                          |
| `bm`                | List bookmarked command lines. Every line indicated a registered command line | Just write `bm`                           |
| `bm r`              | Remove an exist bookmark                                                      | `bm r ssh_myserver`                       |

## License
This project is licensed under Apache 2.0 license
