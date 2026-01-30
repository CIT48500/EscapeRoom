docker commands.txt contains files to build the kali-ssh and kali-rdp docker images.
-> make sure to run the image creation commands in their respective folders (kali-ssh/kali-rdp)

old compose is old. don't use it.

init is required for the compose file to make the base users for the database as well as the database schema.

to add more images to the guac group, edit the compose file to add more images. ensure that the network flag is the same throughout. guacnet is default.
