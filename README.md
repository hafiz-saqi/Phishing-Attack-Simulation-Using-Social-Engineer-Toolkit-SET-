# Phishing Attack Simulation Using Social-Engineer Toolkit (SET)

## 📌 Lab Overview
This lab demonstrates how security professionals simulate phishing attacks using the **Social-Engineer Toolkit (SET)**. The objective is to understand how social engineering attacks work, configure email services securely, and learn how phishing emails can be identified and prevented.

⚠️ **Disclaimer:**  
This lab is performed strictly for educational and defensive security purposes in a controlled environment.

---

## 🛠 Tools & Environment
- Kali Linux
- Social-Engineer Toolkit (SET)
- Gmail
- Virtual Machine Environment

---

## 🧪 Task A: Gmail Setup for SET

### Objective
Prepare a Gmail account for use with SET by configuring secure authentication mechanisms.

### Steps Performed
1. Created a new Gmail account using non-identifiable information.
2. Enabled **2-Step Verification** from Google security settings.
3. Configured **App Passwords** for third-party tool authentication.
4. Generated a 16-character app password for SET usage.

✅ Gmail account is now ready for phishing simulation using SET.

---

## 🎯 Task B: Phishing Attack Simulation Using SET

### Step 1: Launch SET
- Started Kali Linux
- Launched SET from terminal
- Accepted terms and conditions

### Step 2: Configure Phishing Email
SET Menu Options Used:
- Social-Engineering Attacks
- Mass Mailer Attack
- Single Email Address
- Gmail as email provider

Configuration Details:
- Sender email: Gmail account created in Task A
- From Name: Pseudonym (e.g., "Security Alert")
- Authentication: App password
- Priority: High
- Attachments: None

### Step 3: Test Email Delivery
- Phishing email successfully delivered
- Link clicked to verify redirection behavior

📸 Screenshots of SET configuration and email testing are included.

---

## 🧠 Reflection Questions

### Why would a security specialist use SET?
Security specialists use SET to simulate phishing and social engineering attacks in order to:
- Test human-layer security
- Identify weaknesses in awareness
- Train users to recognize phishing attempts
- Improve organizational security policies

### How to Identify a Phishing Email?
Common indicators include:
- Suspicious or misspelled sender addresses
- Urgent or threatening language
- Generic greetings
- Malicious or unexpected links
- Grammar and spelling mistakes
- Requests for sensitive information

---

## 📚 References
1. Kearns, D., O'Gorman, J., & Aharoni, M. (2019). *The Principles of Computer Security*. McGraw-Hill.
2. Kennedy, D., TrustedSec. (2018). *Social-Engineer Toolkit (SET)*.
3. Stallings, W. (2019). *Computer Security: Principles and Practice*. Pearson.
4. Miller, R. (2017). *Hacking: The Art of Exploitation*. No Starch Press.

---

## 🏁 Conclusion
This lab highlights how phishing attacks are conducted and emphasizes the importance of email security awareness. Simulated attacks using SET help organizations understand threats and strengthen defenses against real-world social engineering attacks.
