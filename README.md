# Task-1
import hashlib

password = "mypassword"
hashed = hashlib.sha256(password.encode()).hexdigest()

print(hashed)from cryptography.fernet import Fernet

key = Fernet.generate_key()
cipher = Fernet(key)

message = b"Cybersecurity Basics"
encrypted = cipher.encrypt(message)
decrypted = cipher.decrypt(encrypted)

print(encrypted)
print(decrypted)import socket

s = socket.socket()
s.connect(("example.com", 80))
s.send(b"GET / HTTP/1.1\r\nHost: example.com\r\n\r\n")
print(s.recv(1024))
s.close()query = "SELECT * FROM users WHERE name = '" + username + "'"ls
chmod 777 file.sh
netstat -an
nmap localhost
