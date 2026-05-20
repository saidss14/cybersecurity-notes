# Email & Web Protocols

## 📧 Email Protocols

### SMTP (Simple Mail Transfer Protocol)
- Used to **send emails**
- Works on port **25 / 587 / 465**
- Flow: Sender → SMTP Server → Recipient Mail Server

---

### POP3 (Post Office Protocol v3)
- Used to **receive/download emails**
- Downloads emails to device and may delete from server
- Port: **110 (non-secure), 995 (secure)**

---

### IMAP (Internet Message Access Protocol)
- Used to **access emails on server**
- Emails stay on server (sync across devices)
- Port: **143 (non-secure), 993 (secure)**

---

## 🌐 Web Protocols

### HTTP (HyperText Transfer Protocol)
- Used for communication between browser and web server
- Port: **80**
- Not secure (data in plain text)

---

### HTTPS (HTTP Secure)
- Secure version of HTTP
- Uses encryption (SSL/TLS)
- Port: **443**

---

## 📌 HTTP Headers (Basic)

### Request Headers
- Host → website domain
- User-Agent → browser info
- Accept → data types browser accepts

### Response Headers
- Content-Type → type of data (HTML, JSON, etc.)
- Set-Cookie → stores cookies in browser
- Status Code → response status (200, 404, 500)