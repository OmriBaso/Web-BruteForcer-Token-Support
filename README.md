# Web-BruteForcer-Token-Support
Web-BruteForcer-Token-Support

**About The Tool**  
Simple tool for brute forcing logins which are   
using anti-Automation tokens to stop you from brute forcing them

## Usage

- Example:

  - `python3 brutecsrf.py --url http://test.com/index.php --csrf name_csrf_token_in_HTML_form --u admin --fuser user_name_in_HTML_form --passwd password_name_in_HTML_form`

- Actualy Usage:
  - `python3 brutecsrf.py --url http://test.com/index.php --csrf csrf_token --u admin --fuser username --passwd password`

**If some field doesnt have a name set it as `""`**

## Note

If I will see that people want this kind of a tool
I will make it more professional and automate everything.
PM me on HTB so I will know :)

## Credits

Tool was written by J3wker aka "Omri Baso"
