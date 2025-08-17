# Dev Tools

Just a collection of shell scripts that I'm finally putting in one place. At some point maybe I'll even organize them

### Scripts

#### dockerps 
A tool to select which columns you wish to see out of `docker ps -a` for better readability. 

#### install-vscode
Installs vscode with an init script to start at boot. After first run you must register the tunnel. 

#### node-purge
Starting of as a one-liner it morphed into this, it is intended to cleanup my dev environment on my local machine.  
Useful to nuke Node.js projects without killing MySQL or vscode server. 
It kills all processes running on ports 3000-3305 and 3307-5999 and server.js processes. 
