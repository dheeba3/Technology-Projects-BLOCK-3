# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

(Add screenshot here)

<img width="5712" height="4284" alt="IMG_9360" src="https://github.com/user-attachments/assets/9dd7ea4a-85c5-4cba-9928-774bb93278f3" />

### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes
<img width="5712" height="4284" alt="IMG_9361" src="https://github.com/user-attachments/assets/e369af33-2f4e-4de5-97e3-f8be3083e026" />

Run:

    ps aux

### Screenshot

(Add screenshot here)

### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln
    <img width="4032" height="3024" alt="IMG_9368" src="https://github.com/user-attachments/assets/918d82b8-530d-4cc9-9871-9c9cc7aaaa99" />
<img width="4032" height="3024" alt="IMG_9368" src="https://github.com/user-attachments/assets/281eb60a-b485-4d07-b121-4d750613feef" />
<img width="5712" height="4284" alt="IMG_9367" src="https://github.com/user-attachments/assets/9a9b0006-7baa-404e-aac8-b26262a85ae8" />
<img width="4032" height="3024" alt="IMG_9366" src="https://github.com/user-attachments/assets/0058acfc-0bd6-4101-9249-36204d565b04" />
<img width="4032" height="3024" alt="IMG_9365" src="https://github.com/user-attachments/assets/93ce343d-81b5-48f5-b8c5-121f8e330b51" />
<img width="5712" height="4284" alt="IMG_9364" src="https://github.com/user-attachments/assets/50104d0a-fdb0-421e-8a2d-1564f4fcf599" />
<img width="5712" height="4284" alt="IMG_9363" src="https://github.com/user-attachments/assets/968cf05a-e580-46d3-9464-c801a0825e3b" />
<img width="5712" height="4284" alt="IMG_9362" src="https://github.com/user-attachments/assets/666b00a9-2c50-4844-8bc8-d23e4c182179" />


### Screenshot

(Add screenshot here)

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
