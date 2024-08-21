# Wireshark

## Exploring Network Security: Capturing Login Credentials with Wireshark on Vulnerable Site

Wireshark is a network protocol analyzer that allows users to capture and interactively browse the traffic running on a computer network in real time. It is an open-source tool that helps to troubleshoot network issues, analyze security vulnerabilities, and understand network protocols by capturing and dissecting data packets. Wireshark is available for multiple operating systems, including Windows, macOS, and Linux.

The project demonstrates how to capture/sniff login credentials using Wireshark on vulnerable websites. 

## Objective
The primary goal of this project is to showcase how easily login credentials can be intercepted when they are transmitted over an unsecured network. 

## Outcome
The project will serve as a practical demonstration of the vulnerabilities present in unencrypted networks and highlight the importance of using secure connections.

## Procedures
1. Launch Wireshark.
<img width="949" alt="image" src="https://github.com/user-attachments/assets/e4503e40-d1f8-4855-a84d-c9df7b21aa9d">

2. Access the website (vulnerable website for project demonstration).
<img width="700" alt="Screenshot 2024-08-21 at 11 28 14 AM" src="https://github.com/user-attachments/assets/0f6578d6-f4c3-410d-8972-742926b9b559">

3. Input the login credentials on the site.
<img width="701" alt="Screenshot 2024-08-21 at 11 29 40 AM" src="https://github.com/user-attachments/assets/398d7ee0-c3d4-4250-88a8-5d0d8dbc0f75">
 
4. Wireshark captures packets.
<img width="957" alt="image" src="https://github.com/user-attachments/assets/35e9bc4f-79ec-4fde-8270-78240562793b">
 
5. Wireshark collects various packets, but we'll focus on HTTP packets specifically. We'll search for the GET and POST methods, as these are commonly used to submit form data from web pages, and locate the user-inputted login credentials.
<img width="1194" alt="Screenshot 2024-08-21 at 11 30 50 AM" src="https://github.com/user-attachments/assets/bc0898e3-465a-479c-85bb-b25acd65bb8f">

6. We can easily identify the username and password entered by the user, making it quite simple to locate them.
<img width="1188" alt="Screenshot 2024-08-21 at 11 32 06 AM" src="https://github.com/user-attachments/assets/ae04d4e0-8a1e-4624-9f13-6fdb93d351d4">

The motivation behind this project goes beyond merely demonstrating that our applications or network could be vulnerable or easily sniffed. The project aims to underscore the critical importance of keeping our system or network secure.

To protect our networks from the vulnerabilities demonstrated in the project where Wireshark easily captures login credentials, several key countermeasures should be implemented such as: 
- Use of HTTPS secure communication
- Use of multi-factor authentication (MFA)
- Regular networking monitoring
- Use fo VPN for remote access
- Implement strong access controls
- Regular software/system update
- Awareness & Training 





