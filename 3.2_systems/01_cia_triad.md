# Exploring the CIA Triad

## Objective

Understand the **Confidentiality, Integrity and Availability (CIA)** principles using practical tasks on a Raspberry Pi.

---

# Part 1 – Confidentiality

1. Create a confidential file.

    ```bash
    nano secrets.txt
    ```

1. Write some confidential information.

1. Save the file.

1. Now restrict access:
    ```bash
    chmod 600 secrets.txt
    ```
1. Check permissions:
    ```bash
    ls -l secrets.txt
    ```

**Questions**
- Who can read this file? just me
- How does file permission protect confidentiality?It prevents unauthorised users from accessing or reading private information.

## Part 2 – Integrity

1. Create a hash of the file.
    ```bash
    sha256sum secrets.txt
    ```
    _What does "hash" do?It creates a unique digital fingerprint of the file's contents.

1. Save the output.

1. Modify the file.
    ```bash
    nano secrets.txt
    ```

1. Run the hash again.


** Questions**
- Did the hash change?Yes, modifying the file should produce a different hash.
- Why do security systems use hashing?To check data integrity and detect whether a file has been changed or tampered with.


# Part 3 – Availability

1. Check system uptime:
    ```bash
    uptime
    ```

1. List running processes:
    ```bash
    top
    ```

**Questions**
- Why is system uptime important?It ensures that systems and services remain accessible to users when needed.
- What happens if a system is unavailable?Users cannot access data or services, which can cause disruption and loss of productivity.

## Deliverables
Include:
- Screenshot of file permissions
- Screenshot of hash results
- Answers to questions
- Reflection
    >Explain how this activity demonstrated the CIA triad.
<img width="5712" height="4284" alt="IMG_9410" src="https://github.com/user-attachments/assets/2e5c83fa-65c7-4f8c-b3d2-a1217d0fce45" />
