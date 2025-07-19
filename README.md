# ADVANCED-ENCRYPTION-TOOL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DEV MANISHKUMAR RATHOD

*INTERN ID*: CT04DH2886

*DOMAIN*: CYBER SECURITY AND ETHICAL HACKING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:

As the final task of my Cyber Security & Ethical Hacking internship, I developed a robust file encryption and decryption tool using Python. The goal was to build a secure application that can protect the contents of any file using advanced encryption algorithms, specifically AES (Advanced Encryption Standard). This tool ensures that sensitive data remains confidential and inaccessible without the correct decryption key.

The tool is built using Python’s cryptography library, which provides a safe and easy-to-use interface for implementing encryption. I used Fernet encryption, which handles key generation, AES encryption, and message authentication internally to simplify the process and reduce risks of errors. While Fernet is based on AES (128-bit), it provides strong security suitable for most real-world use cases, and follows best practices for safe encryption.

The script works through a simple, user-friendly menu interface in the command line. Users can generate a secure key, which gets saved in a file called secret.key. This key is then used to encrypt and decrypt files. Once a file is encrypted, a new file with .enc extension is created. Similarly, when decrypting, the tool creates a .dec version of the original file. This way, users never lose the original content unless they explicitly delete the old files.

One of the most important lessons I learned during this task was the significance of secure key management. Without the correct key, encrypted files become unreadable, which shows how strong encryption can be both a powerful defense and a potential risk if not handled carefully. That's why the tool ensures the key is saved locally in a file so users can back it up safely.

This project helped me understand how encryption works in practice, beyond just the theory. It taught me how data can be protected in storage, how files are transformed into unreadable ciphertext, and how cryptographic libraries abstract complex algorithms into simple, usable tools for developers. I also realized the importance of making security tools easy to use, because even the most secure encryption is useless if it's too complicated for users to adopt.

Overall, building this tool was a great hands-on experience in applied cryptography. It gave me insight into how encryption tools are built and used in the real world to protect data, whether it’s for personal privacy, secure backups, or sensitive communications. I now feel more confident about building security-focused applications and using encryption as part of my development toolkit.

*OUTPUT*:

