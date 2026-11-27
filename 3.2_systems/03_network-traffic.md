# Observing Network Traffic on Rapsberry Pi

## Task 1 --- Install tcpdump

Run:

    sudo apt install tcpdump

### Screenshot

(Add screenshot)

------------------------------------------------------------------------

## Task 2 --- Capture Network Traffic

Run:

    sudo tcpdump

Let the capture run for about 20 seconds.

### Screenshot

(Add screenshot)
<img width="3024" height="4032" alt="IMG_9417" src="https://github.com/user-attachments/assets/69e8d107-99bf-4a47-a122-de9ef970a3d4" />
<img width="5712" height="4284" alt="IMG_9418" src="https://github.com/user-attachments/assets/6da2d3df-fb89-470c-9039-e0d3c97026b9" />

### Questions

1.  What types of traffic do you observe?Common types include TCP, UDP, DNS and HTTPS traffic.
2.  Can you identify IP addresses?Yes, the source and destination IP addresses can be identified in network packets
3.  Do you see DNS queries?
DNS queries may appear when the system requests the IP address of a domain name
### Reflection

Explain what network monitoring can reveal about system activity.

------------------------------------------------------------------------

## Task 3 --- Security Discussion

### Questions

1.  Could sensitive information appear in network traffic?Yes, sensitive information such as passwords and personal details can be exposed if the traffic is unencrypted.
2.  Why is HTTPS important for protecting communications?HTTPS encrypts data, preventing unauthorised users from reading or modifying information during transmission.

### Reflection

Describe what you learned about network visibility and security.I learned that network visibility helps us understand how devices communicate and detect security threats. I also learned that encryption protects sensitive information and keeps network communications secure.
