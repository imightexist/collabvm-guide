# collabvm-guide
CollabVM guide for dumbass people
# 3.0
nothing yet
# 1.2.11
## linux compiling server
Download and extract collab-vm-server from https://github.com/computernewb/collab-vm-server/tree/release/1.2.11
1. go to scripts folder
2. sudo apt install build-essential (debian/ubuntu command, for arch: sudo pacman -S base-devel)
3. do "./grab_deps_linux.sh"
4. do "make JPEG=1"
5. now you can move on to the webserver part
## precompiled server (for windows users and lazyass people)
download from here: https://github.com/computernewb/collab-vm-server/releases/1.2.11 and move on to the webserver part
## webserver
1.2.11 no longer comes with a webserver, so you have to do it yourself. nothing here for that yet
# webapp
1. install nodejs (windows: nodejs.org, ubuntu/debian: sudo apt install -y nodejs npm, arch: sudo pacman -S nodejs npm)
2. do "npm install --global gulp-cli"
3. express for webserver, optional: "npm install --global express"
4. go to the webapp directory
5. type in "gulp"
6. in the build folder is the webapp. copy this over to the http folder in the server
7. if there is any "file already exists" errors, just click replace all
8. now move on to the webserver step if you're doing 1.2.11, if not, move on to the finalizing server part
# finalizing the server
1. install qemu
2. (adding more steps later)
# 1.2.10
