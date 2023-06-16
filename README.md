# PhisingIncident
Ticket ID:A-2703  / Alert Message:Server-Mail Phishing attempt possible download of malware. / Severity: Medium / Details: User may have opened malicious attachments. / Ticket status: Escalated

Ticket Comments:
The alert has identified that an employee has downloaded and opened a malicious file from a phishing email. There are inconsistencies observed within the email, such as the sender's email address being "76tguy6hh6tgftrt7tg.su," the name used in the email body being "Clyde West," and the sender's name being "Def Communications." Additionally, both the email body and subject line contain grammatical errors. The email's body also includes an attachment named "bfsvc.exe," which is password-protected and was successfully downloaded and opened on the affected machine. Upon prior investigation, it has been confirmed that the file hash corresponds to a known malicious file. The severity of the alert has been categorized as medium. Considering these findings, I have decided to escalate this matter to a level-two SOC analyst for further necessary action.

Additional information
Kown malicious file hash:54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Email:
From: Def Communications <76tguyhh6tgftrt7tg.su> <114.114.114.114>
Sent: Wednesday, July 20, 2022 09:30:14 AM
To: <hr@inergy.com> <176.157.125.93>
Subject: Re: Infrastructure Egnieer role
Dear HR at Ingergy,
I am writing for to express my interest in the engineer role posted from the website.
There is attached my resume and cover letter. For privacy, the file is password protected. Use
the password paradise10789 to open.
Thank you,
Clyde West
Attachment: filename="bfsvc.exe"
