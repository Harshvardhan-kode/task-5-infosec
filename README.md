# task-5-infosec

# Client-Side vs Server-Side Security

## Client-Side Security
This security runs in the user's browser.

### Examples
- JavaScript checks
- Form validation (required, min, max)
- Disabled buttons

### Good Things
- Fast
- Better user experience

### Bad Things
- Easy to bypass
- User can change it using browser tools


## 📄 `02-http-methods-and-headers/notes.md`

# HTTP Methods & Headers

## HTTP Methods
They tell the server what action to do.

### Common Methods

- GET → get data
- POST → send data
- PUT → update data
- DELETE → delete data
- PATCH → partial update

### Security Notes
- GET shows data in URL
- POST hides data but is not encrypted
- Wrong method usage can cause attacks

---

## HTTP Headers
Extra information sent with requests.

### Common Headers
- Host → website name
- User-Agent → browser info
- Cookie → session data
- Authorization → login token
- Content-Type → data format

### Security Headers
- CSP → stops XSS
- HSTS → forces HTTPS
- X-Frame-Options → stops clickjacking

### Example Request

POST /login HTTP/1.1
Host: example.com
Content-Type: application/json

##  `03-ssti/notes.md`

# Server-Side Template Injection (SSTI)

## What is SSTI?
When user input is executed by the server template engine.

---

## How It Happens
- User input is directly rendered
- No proper filtering

### Bad Example
