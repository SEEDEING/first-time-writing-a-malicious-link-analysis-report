# first-time-writing-a-malicious-link-analysis-report
This is my first time writing a malicious link analysis report; I welcome feedback from more experienced colleagues. 🤝  

I received an email from an unknown sender with the subject line “Latest Release from the Ministry of Public Security: List of Individuals Illegally Staying in Southeast Asia, the UAE, and Other Regions,” which contained a short link. I ran it through a sandbox (an isolated virtual machine where suspicious links can be safely opened) for analysis.

My conclusion: Suspicious—likely a phishing attempt (using a fake page to trick users into entering their login credentials), with a moderate confidence level.
There’s no single piece of evidence to prove this; rather, several weak indicators point in the same direction:
• The email uses an “official + alarming” subject line to urge recipients to click
• The short link hides the actual destination
• besaegis[.]org was registered just 6 days ago and has been flagged as suspicious
• The page code is obfuscated (intentionally written to be unreadable)

What the sandbox didn’t detect: downloading malicious software or connecting to the attacker’s command-and-control server. However, the sandbox also failed to capture the page’s actual content, so “not detected” does not equate to “safe.”

I’m aware of my limitations: I lack a complete redirection path, page screenshots, decrypted obfuscated code, and email headers.

I’d like to ask for your advice:

If this were you, which piece of evidence would you prioritize gathering next?
Are my corresponding ATT&CK identifiers reasonable?
Is the “moderate confidence” assessment appropriate?

All links and IP addresses have been neutralized (defanged); please do not click on them.
<img width="5100" height="6600" alt="Malicious_Link_Sandbox_Analysis_Report_page_1" src="https://github.com/user-attachments/assets/405da8ad-5dc4-4a62-bba2-18d21e405b4b" />
<img width="5100" height="6600" alt="Malicious_Link_Sandbox_Analysis_Report_page_2" src="https://github.com/user-attachments/assets/d636e9e0-da10-4cba-ba47-798de1336469" />
<img width="5100" height="6600" alt="Malicious_Link_Sandbox_Analysis_Report_page_3" src="https://github.com/user-attachments/assets/5b33ea3c-cf17-4387-87b4-672dcc68700c" />
<img width="498" height="581" alt="WhatsApp Image 2026-11-12 at 2 52 18 PM" src="https://github.com/user-attachments/assets/430bc459-e0fa-41fb-9001-0116ee7ec838" />

