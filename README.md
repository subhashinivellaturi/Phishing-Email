# Phishing Email Analysis Report – Task 2

This report analyzes a sample phishing email to identify potential phishing indicators. The analysis follows 8 specific checks, including sender spoofing, suspicious links, urgency in language, attachments, and grammar issues. The sample was opened and reviewed using Kali Linux.
##Phishing Indicators

## 1. Sample Source
The phishing email was obtained from an online phishing simulation (CanIPhish). Files used for analysis:
- phish.html (email content)
- phishing.png (email screenshot)

## 2. Sender Address Spoofing
The sender email used a fake domain: `microsoft@email-records.com`. This is not an official Microsoft domain, which indicates spoofing.

## 3. Email Header Check
Not available for this file type (.html), so header analysis was skipped.

## 4. Suspicious Links or Attachments
The email contains a button labeled "View Alert Details" that leads to a suspicious URL. There is also a `.docx` file attached, which could be malicious.


## 5. Urgent Language
The email uses fear-based language like "High-severity alert triggered", encouraging the user to act immediately.


## 6. Mismatched URLs
The button appears to go to Microsoft, but the actual link leads to a different, suspicious domain. This is a common phishing trick.

## 7. Grammar or Spelling Errors
Grammar issues were observed: "Sent by Unknown to at time 01/22/2021". This indicates poor language quality, typical of phishing emails.


## 8. Summary of Phishing Traits
- Fake sender address
- Suspicious link behind buttons
- Malware-style `.docx` attachment
- Urgent tone to create panic
- Poor grammar and sentence structure
- Fake Microsoft branding

### Conclusion:
This email is a phishing attempt that uses urgency and social engineering to trick users into opening a file or clicking a malicious link.


##Tools Used
## Tools Used
- Firefox (to open phish.html)
- xdg-open (to view phishing.png)
- Terminal tools: cat, strings


