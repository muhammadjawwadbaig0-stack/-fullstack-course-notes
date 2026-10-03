# Module 1 — Answers

## Computer Fundamentals

### 1. Name the three-stage cycle every computer performs.

**Answer:**  
Input, processing, and output.

---

### 2. Give one example each of hardware and software on your own machine.

**Answer:**  
Examples of hardware are a monitor, CPU, and keyboard.  
Examples of software are Windows and Microsoft Office.

---

### 3. What's the difference between a CPU core and a thread?

**Answer:**  
A CPU core is a physical processing unit inside the CPU that can execute instructions. A thread is a sequence of instructions that a CPU core can execute. Some CPU cores can handle two or more threads at the same time.

---

### 4. Why is RAM described as "volatile"?

**Answer:**  
RAM is described as volatile because it loses its stored data when the power is turned off.

---

### 5. Name two differences between an HDD and an SSD.

**Answer:**  
An HDD is slower and uses magnetic disks. It has moving mechanical parts.  
An SSD is faster and uses NAND flash memory. It has no moving parts and is usually more expensive than an HDD.

---

### 6. List three responsibilities of an operating system.

**Answer:**  
An operating system manages hardware, manages files and storage, and manages software/applications and running processes.

---

### 7. What's the difference between a program and a process?

**Answer:**  
A program is a set of instructions, while a process is the execution of a program.

---

### 8. What's the difference between a compiled and an interpreted language?

**Answer:**  
A compiled language is translated into machine code before the program runs. In an interpreted language, the code is interpreted during runtime.

---

### 9. Why can Git track line-by-line changes in a `.js` file but not in a `.png` file?

**Answer:**  
A `.js` file is text-based, so Git can read and compare it line by line. A `.png` file is a binary file, so its data does not have meaningful lines of text to compare.

---

### 10. Why does a file extension matter even though it doesn't change the file's actual content?

**Answer:**  
A file extension helps the operating system and applications identify what type of file it is and which program should open it.

---

## Web Basics

### 11. Explain the difference between "the internet" and "the web" in your own words.

**Answer:**  
The internet is a global network that connects computers and other devices. The web is a service that runs on top of the internet and allows us to access websites and web pages.

---

### 12. Draw (on paper) the client-server request/response cycle for loading a web page.

**Answer:**  
The client sends an HTTP request to the server. The server processes the request and sends back an HTTP response containing a status code and usually the requested content.

---

### 13. What does DNS do, and why is it necessary?

**Answer:**  
DNS translates a domain name into an IP address. It is necessary because humans can remember names like `github.com` more easily than numerical IP addresses.

---

### 14. Name the 5 HTTP methods and one use-case for each.

**Answer:**  

- **GET** — requests or retrieves content.
- **POST** — creates new data, such as creating a new user.
- **PUT** — replaces an entire existing resource.
- **PATCH** — updates part of an existing resource.
- **DELETE** — deletes a resource completely.

---

### 15. Explain why HTTP is described as "stateless," and how cookies/sessions address that.

**Answer:**  
HTTP is stateless because each request is independent and HTTP does not automatically remember previous requests. Cookies and sessions can store or identify information so the server can recognize a user between different requests.

---

### 16. What does HTTPS add on top of HTTP?

**Answer:**  
HTTPS uses TLS to encrypt and protect communication between the client and server.

---

### 17. What is an API, and why don't frontend and backend just share one program directly?

**Answer:**  
An API is a way for two software components to communicate without needing to know about each other's internal functionality. It allows the frontend and backend to communicate while remaining separate parts of an application.

---

### 18. Convert this into a REST-style endpoint: "get all comments on post 15" and "delete comment 9 on post 15."

**Answer:**  

**Get all comments on post 15:**

```text
GET /posts/15/comments