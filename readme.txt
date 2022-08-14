Yum configuration is easy to setup here are steps to install.

Step 1:
Attach the dvd.iso file which was used to install the linux machine.

Step 2:
Create a directory where the attached dvd.iso can be mounted.

Step 3:
Mount the dvd to the directory by using the command,
	mount /dev/sr0 /path-to-new-directory

Step 4:
Copy the file named "AppStream" from the dvd.iso to /mnt.
Copy the file named "BaseOS" from the dvd.iso to /mnt

Step 5:(Use the packages.repo file for refrence)
Now create a packages.repo file in /etc/yum.repos.d/

Step 6:
Check if the configuration is correct by using command,
	yum update -y