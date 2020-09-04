# Apollo Client State with React Starter Project

This project is for used with the Mastering Apollo Series on WintellectNOW [http://www.wintellectnow.com](http://www.wintelltectnow.com)

## Project Setup

### Requirements

- Node.js (version 8 or later)
- Web Browser

### Instructions

**Step 1.** Clone/Download this repository. If downloading the zip file, then extract the zip file.

**Step 2.** Open a terminal window and change to the folder containing the "package.json" file.

**Step 3.** Run the following commands:

```bash
npm install

npm run start-rest-server
```
**Step 4.** Open a second terminal window and change to the folder containing the "package.json" file.

**Step 5.** Run the following command:

```bash
npm run start-graphql-server
```
**Step 6.** Open a third terminal window and change to the folder containing the "package.json" file.

**Step 7.** Run the following command:

```bash
npm run start-client
```

**Step 8.** Your system's default web browser should open and browse to the URL http://localhost:3000.

### Modifying the Project

The server files can be modified in the "server-src" folder. The "server-dist" folder is generated by the "start-server" command. Do not edit the files in the "server-dist" folder as they will be overwritten. The client files can be modified in the "public" and "src" folders. The "src" folder contains the JavaScript code for the Apollo Client and React Components.

### FAQ

**Question 1.** If you have another version of Node.js installed on your system which does not work with this course, then please consider installing [NVM](https://github.com/creationix/nvm) (for Mac & Linux) or [NVM-Windows](https://github.com/coreybutler/nvm-windows) to enable the installation of multiple versions of Node.js. Both tools support the installation, management and switching between multiple versions of Node.js. Using these tools, installing Node.js version 8 or later without losing your older version should be possible. This course does not provide support for these tools, the course only suggests using them if needed.

**Question 2.** The default ports number for the three server applications are as follows:

  - Web Server: 3000
  - GraphQL Server: 3010
  - REST Server: 3020

  If your system is running programs on these ports there will be a conflict when these three servers are started. Either disable the other applications running on those ports or change the port numbers for this project's servers within your "package.json" file. To change the port numbers, modify the port values specified in the "config" section of the "package.json". No changes to the JavaScript code is needed as the code reads the environment variables set by the config section.

**Question 3.** If you are running on Windows and running the above "npm" commands with Cygwin Bash then substitute the above commands with these:

```bash
npm run start-rest-server-cygwin

npm run start-graphql-server-cygwin

npm run start-client-cygwin
```

If you are using the Windows Command Prompt (default on Windows), then use the original commands listed in the instructions.
# Apollo-client-state-mangement
