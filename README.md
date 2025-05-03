# EnvHunter

EnvHunter is a simple but powerful Python tool to:

✅ Automatically search for `.env` files  
✅ Parse environment variables from `.env` files  
✅ Extract secrets like AWS Keys, DB Passwords, API Keys  
✅ Save results to report for auditing or leak hunting

Perfect for security researchers, leak hunters, or developers auditing repos and servers for accidental secret leaks.

## Usage

python3 envhunter.py /path/to/scan

## Output

.env found at /target/.env

AWS_ACCESS_KEY_ID=AKIAxxxxxxxxx
DB_PASSWORD=mydbpassword
MAIL_PASSWORD=xxxxxx

Saved to report.txt
