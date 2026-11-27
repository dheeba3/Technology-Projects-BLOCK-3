# Detecting Suspicious Activity

## Objective

Learn about **detective security controls**.

---

## Step 1 – View authentication logs

```bash
sudo cat /var/log/auth.log
```

## Step 2 – Search for login attempts
```bash
grep "Failed password" /var/log/auth.log
```

## Step 3 – View recent logins
```bash
last
```

## Questions
- What information appears in authentication logs?Authentication logs can contain usernames, IP addresses, login times, successful logins and failed login attempts.
- Why are logs important in cybersecurity?Logs help monitor system activity, detect security threats and investigate unauthorised access.
- What might indicate suspicious activity?Repeated failed login attempts, unfamiliar IP addresses and logins at unusual times could indicate suspicious activity.


## Deliverables
Include screenshots of:
<img width="5712" height="4284" alt="IMG_9426" src="https://github.com/user-attachments/assets/4e5b48a7-ee2e-45f6-a14a-9008d4cfab4b" />

<img width="5712" height="4284" alt="IMG_9424" src="https://github.com/user-attachments/assets/ff2375df-393a-4220-a078-58eed1693a61" />

- authentication logs
- failed login search results
