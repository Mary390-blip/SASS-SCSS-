sass
 # Steps to install SASS on Ubuntu for ALX project 0x03-sass_scss

 Ran the NVM installation script:
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

 Exited the terminal using the 'exit' command and reopened a new terminal session.

 Verified NVM was installed:
   nvm --version
   # Output: 0.39.7

Installed the required Node.js version using NVM:
   nvm install 20.16.0

Set the new Node version as the active version:
   nvm use 20.16.0

 Verified Node and NPM versions:
   node -v # Output: v20.16.0
   npm -v  # Output: 10.8.2

 Installed SASS globally using NPM with the specific version:
   npm install -g sass@3.7.4

 Verified the SASS installation:
   sass --version
   # Output: 3.7.4
   
guillaume@ubuntu:~/$ sass 0-debug_log.scss | head -n 0
0-debug_log.scss:2 DEBUG: Hello world

guillaume@ubuntu:~/$ 
  @debug $your-variable;
@debug "Hello world";

