
---

## 🛠️ Tools Used
- Free Online Header Analyzers:
  - [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- VirusTotal for URL analysis
- Manual inspection of email content, tone, and structure

---

## 🧩 Phishing Indicators Found

| Indicator                            | Description |
|----------------------------------    |-------------|
| 🔗 **Suspicious URL**               | Mismatched domain: looks like Microsoft but points to `verify-account-security.com` |
| 📩 **Spoofed Email Address**        | Sender domain is a misspelled version of `microsoft.com` |
| ⚠️ **Urgent/Threatening Language** | Claims of account suspension within 24 hours to provoke panic |
| ❌ **Generic Salutation**          | Uses "Dear User" instead of recipient's name |
| ✍️ **Awkward Language**            | Unnatural phrasing like "verify your identity now" |
| 🚫 **Missing Branding**            | No logos, legitimate contact details, or professional formatting |
| ❓ **SPF/DKIM/DMARC Failures**     | Header analysis showed missing or failed authentication checks |

---

## ✅ Conclusion
The analyzed email is a **phishing attempt**. It uses urgency, spoofing, and deception to lure users into clicking a malicious link. Users are advised **not to interact** with such emails and to report them to security teams.

---

## 📚 Outcome
- Improved awareness of phishing tactics  
- Hands-on experience analyzing real-world threats  
- Developed skills in email header inspection and content analysis

---

## 📎 References
- [How to Read Email Headers](https://www.huntress.com/blog/how-to-read-email-headers)
- [Phishing Indicators by CISA](https://www.cisa.gov/news-events/news/avoiding-social-engineering-and-phishing-attacks)
