# Ubuntu Demon Creator
An automated way of creating services/demons for ubuntu 16.04.

I made this script for other automated bash scripts and to fix some bugs in this https://gist.github.com/naholyr/4275302.

## Example
	curl https://github.com/chazmaniandinkle/ubuntu-demon-creator/blob/master/create-demon.sh | sudo name="web" username="web" command="/home/web/start.sh" description="Basic web server" bash
### Logs
	/var/log/<name>.log
### Removal
	service uninstall <name>
## Parameters
* name: Name of the demon.
* username: The user the demon will run as.
* command: The command to run the demon.
* description (optional): The description of the demon.
