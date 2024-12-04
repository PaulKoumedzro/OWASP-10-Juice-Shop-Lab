# OWASP-10-Juice-Shop-Lab

# Objective

The objective of the OWASP Juice Shop lab is to provide hands-on experience in identifying and exploiting common web application vulnerabilities in a controlled environment. The key concept is to learn about ecurity concepts, including the OWASP Top Ten vulnerabilities, while practicing ethical hacking techniques such as input validation testing, authentication bypass, SQL injection, cross-site scripting (XSS), and more. The lab aims to enhance participants penetration testing skills, foster a deeper understanding of application security risks, and promote secure coding practices.


# Skill Learned
- Learning to identify insecure coding patterns that lead to vulnerabilities.
- Assessing weak authentication mechanisms and testing session management flaws.
- Dynamic Application Security Testing (DAST)
  

  # steps
Fig1: The OWASP juice Shop website
![Screenshot 2024-11-28 at 08-58-31 OWASP Juice Shop](https://github.com/user-attachments/assets/97650d74-0b96-4d80-b937-56d73db69968)

Fig2: The screenshot below shows sensitive Data exposure in the product review which correspond to the OWASP top 10 Cryptographic failures.
![Screenshot 2024-11-28 at 09-02-20 OWASP Juice Shop](https://github.com/user-attachments/assets/990f6c66-0995-44d8-b13a-3d844c31e4f9)

Fig3: Testing the login form (authentication) mechanism. A random login iformation is provided forwarded to Burp Suite.
![Screenshot 2024-11-28 at 09-22-05 OWASP Juice Shop](https://github.com/user-attachments/assets/857e6f2d-1a02-4663-a17b-acaa3349e7db)

Fig4: Burp Suite is used to intercept the credentials
![2](https://github.com/user-attachments/assets/1220f549-ffba-4ed3-904f-f34e0f1764c3)

Fig5: Burp Suite will modify the captured data and forward back to the server to 
![3](https://github.com/user-attachments/assets/68866087-73f6-40de-8ed5-3cf0d438854a)

Fig6: I was able to login to the into the admin dashboard and access the data because improper input validation and broken authentication mechanism.
![4](https://github.com/user-attachments/assets/575b366d-21bb-42cf-b515-8c0651cf5886)



  # Recommendations
Use the recommendations to secure the website
- Sanitize Inputs: Use parameterized queries or prepared statements to prevent injection attacks.
- Use Input validation: Validate user inputs against strict patterns (e.g., regex) to filter out malicious data.
- Strong Password Policies: Enforce strong passwords using complexity, length, and uniqueness rules.
- Rate Limiting: Implement rate limiting to prevent brute force attacks.
