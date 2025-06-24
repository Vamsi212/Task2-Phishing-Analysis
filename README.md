#  Phishing Email Analysis - Task 2 Report

## 🎯 Objective

Analyze a suspicious email and identify phishing indicators based on spoofing, header analysis, and social engineering techniques.

---

## 📥 Sample Email (Netflix Phishing)

From: Netflix Support <support@netflxbilling.com>  
Subject: Your Account Has Been Suspended  

Dear Customer,  

We were unable to validate your billing information for your Netflix account.  
To avoid interruption of your subscription, please update your payment details immediately.  

Click here to update: http://netflix-billing-update.com  

Failure to do so within 24 hours will result in permanent suspension of your account.  

Thank you,  
Netflix Billing Team

---

## ⚠️ Phishing Indicators Identified

| # | Indicator | Explanation |
|---|-----------|-------------|
| 1 | **Spoofed Email Address** | `@netflxbilling.com` is fake – Netflix's real domain is `@netflix.com` |
| 2 | **Urgent Language** | "Your account will be permanently suspended in 24 hours" creates panic |
| 3 | **Fake Link** | Hovering reveals link goes to `http://netflix-billing-update.com`, not Netflix |
| 4 | **Generic Greeting** | Uses "Dear Customer" instead of your actual name |
| 5 | **Grammar Issues** | Small issues in sentence structure and punctuation |
| 6 | **Unusual Domain** | The sending domain isn’t a valid Netflix server |
| 7 | **Social Engineering** | Exploits fear of losing service to make user click quickly |

---

## 🛠️ Tools Used

- Header inspection : MxTooLBox Header Analyzer
![image_alt](https://github.com/Vamsi212/Task2-Phishing-Analysis/blob/56180d647420f814807a9d9f3523eae70ba77414/screenshots/Screenshot%20(377).png)
- Visual analysis
- Hover-over link check
- Domain lookup

---

## ✅ Conclusion

This email is a **classic phishing attempt** designed to steal user login and payment credentials by impersonating Netflix. It uses spoofing, urgency, and a fake link.

---

## 📁 Repo Contents

- `phishing_sample.txt` – the fake phishing email
- `README.md` – this report

---

## 🔒 Safety Tip

Always check email addresses, hover over links, and avoid clicking unexpected emails. If unsure, go directly to the website (e.g., type `netflix.com` in the browser yourself).
