# Week Report 4

## Question 1: Navigating the Filesystem

The presentation goes over the fundamentals of the Linux file system and how to navigate it. A **file system** is how files are organized so that a user can access its data easily. In Linux, all files are organized in a hierarchial directory structure. The highest level directory in this system is the root directory which contains everything the computer is comprised of. 

Any directory you are working is the **current directory**. The immediate previous directory housing the current directory is the **parent directory**. Opening a terminal window or a file manager window sets the current directory as your **home directory**. This is not the same as the home directory for a user which is the top-level directory that said user can access.

Every file or folder in a file system has a **pathname** which identifies where it is. Pathnames can be **absolute** which is the location of the file starting from the root, or **relative** which is the location of a file within the current directory. The file system is represented graphically in Ubuntu.

The commands used to navigate the file system are listed below:

| **Command** | **Description**                                      | **Example**                                                                      |
|-------------|------------------------------------------------------|----------------------------------------------------------------------------------|
| pwd         | displays the current working directory               | using pwd in a terminal will return the current working directory as a pathname  |
| cd          | changes the directory to another specified directory | cd $HOME will change the directory to the home directory of the user             |
| ls          | displays all the files in a specific directory       | ls -a ~/Foldername will list every file within Foldername including hidden files |

## Question 2: Right to Repair

Right to repair is the idea that users who purchase electronic devices are able to repair or make modifications to their devices as seen fit. The right to repair movement is a movement that strives to globalize this idea by pushing for proposals that will make information, parts, and software freely available so that consumers can enact their repairs. This movement matters because as time goes on, companies continue to make items more disposable by making them difficult to repair so that people will continue to buy their products repeatedly. Without right to repair, consumers are pushed to spend more money to either buy a new product or send the product back to its producer for repair so that revenue from that service can be generated.
