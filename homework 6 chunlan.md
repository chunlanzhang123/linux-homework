#  Linux Exercise
## Chunlan Zhang
## 02122025
- Part 1: Understanding APT & System Updates 
- Part 2:Installing & Managing Packages
- Part 3: Removing & Cleaning Packages
- Part 4: Managing Repositories & Troubleshooting
## complete the steps
# Part 1: Understanding APT & System Updates
- Run the virtual machine and complete the link in the terminal
![run](1start.png)
- Check APT version: 
apt --version - instal kolourpaint
[step2](220.png)
- Note that there are no other symbols in the input format
![step2](3bu.png)
- Indicates that kolourpaint has been successfully installed and the version is 
4:23.08.5-0ubuntu3
![step2](3pao.png)
# Part 3: Removing & Cleaning Packages

- remove kolourpaint
![step3](4pao.png)
remove: Only removes the package files, but retains the user's configuration files.
purge: Delete software package files and related configuration files for a more thorough cleanup
- Automatically clean up unused dependencies, which can free up disk space
# Part 4: Managing Repositories & Troubleshooting
- Clear downloaded package files stored in apt folder
![step4](5pao.png)
different folder
- The command will enable the specified repository.
Refresh repository information
![step4](6pao.png)
- Try installing a non-existent package
Unable to locate package fakepackage
use apt search fakepackage and try toConfirm repositories are enabled: Check if the necessary repositories are enabled in the file.
Refresh repository information

## Bonus Challenge
![bonus](7pao.png)
Prevent the trouble caused by unexpected updates