1. Import tkinter module and requests module
2. format and create a UI interface 
3. request kanye quotes from API ENDPOINT (http://api.kanye/rest/)
 # NB SSLError bug
this bug was due to the request module proxy specification, I changed for https:// to http:// 
and fixed the bug.

4. format get_quotes() function to change tkinter label on a button press command. 
