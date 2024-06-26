# FTP Server

Implement an FTP server that allows users to authenticate and list, retrieve, and store files.

## Commands

The FTP server should implement the following commands:

- `USER <username>`: This command should be used to authenticate a user. The server should check if the user exists and if it does, ask for the password.
- `PASS <password>`: This command should be used to authenticate a user. The server should check if the password is correct and if it is, allow the user to execute other commands.
- `LIST`: This command should list all the files in the current directory.
- `RETR <filename>`: This command should be used to retrieve a file from the server.
- `STOR <filename>`: This command should be used to store a file on the server.
- `QUIT`: This command should be used to disconnect from the server.

The server should be able to handle multiple clients at the same time.
Also ensure proper error handling. For example, if a user tries to retrieve a file that does not exist, the serve