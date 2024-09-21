# Inclass Assignment

* Q1: The server is not listening on port 80, so in the lab.js file script, so super user privileges are not needed.
* Q2: The lab.js script file reads the contents of the `plain.txt' file to a buffer, converts it into a string to display in the console.
* Q3: It's using an anonymous callback function, so the after readFile does not have to wait to be displayed on the console while the file contents are being fetched.
* Q4: The function toString('utf-8') converts the buffer from Hex ascii values to a javascript object encoded to Unicode characters.
* Q5: The local browser decodes the bytes to unicode or the prefererd character set.
* Q6: Include conditional statements with checks for MIME types in the readFile function.
* Q7: Possibly use an API to handle queries/routes.

