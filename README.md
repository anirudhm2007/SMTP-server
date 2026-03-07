# Project Title
Node.js SMTP (Simple Mail Transfer Protocol) Server

## Project Description
A lightweight SMTP server designed to receive, process, and log incoming email streams. Deployed on AWS EC2 and routed via Cloudflare.

## Objective
The objective of this project is to understand and implement the mechanism behind electronic mail transmission. By implementing a custom SMTP server, we aim to understand about DNS servers, Node.js, SMTP ports and the usage of AWS EC2 instances & Cloudflare DNS routing.

## Screenshots
<img width="611" height="293" alt="ReadmeAttachment1" src="https://github.com/user-attachments/assets/90cc0974-231d-44fa-9854-1f0a0c863061" />
<img width="1402" height="346" alt="Screenshot 2026-03-06 at 7 17 13 PM" src="https://github.com/user-attachments/assets/ffef3c51-006f-4409-a057-077b0ab7c8bc" />
<img width="912" height="483" alt="image" src="https://github.com/user-attachments/assets/e89bf267-626a-4aaf-9b95-87b6e6e7454e" />



## Hosted URL
This is a backend SMTP server and cannot be accessed via a web browser. To test the server, send an email to any address at this domain:  
address@aniirudh.me <br>
address@rjainil.me <br>
address@palksh.me

These are the email addresses of the custom domain names purchased from Namecheap.

## Features Implemented

### Frontend
N/A (Backend-only application)

### Backend
- Listens for inbound SMTP traffic on TCP port 25.
- Captures and logs sender (onMailFrom) and recipient (onRcptTo) metadata.
- Processes raw email data streams and outputs them directly to the console.
- Executes via standard Node.js runtime attached to the active terminal session.

## Technologies/Libraries/Packages Used
- Runtime: Node.js  
- Libraries: smtp-server  
- Infrastructure: AWS EC2  
- DNS/Networking: Cloudflare  

## Local Setup

- Clone the repository: git clone [https://github.com/anirudhm2007/SMTP-server]
- Install dependencies: ```npm install```
- Start the server: ```sudo node index.js```

  
## Team Members
1. Anirudh Madhavan (2025IMT-006) 
2. Palksh Upadhyay (2025BCS-059)
3. Jainil Rathwa  (2025BCS-072)
