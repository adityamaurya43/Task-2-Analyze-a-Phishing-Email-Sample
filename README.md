# Task-2-Analyze-a-Phishing-Email-Sample

# Objective:
Identify phishing characteristics in a suspicious email.

# Sample Phishing Email:

From: Facebook Support <support@facebooksecure-support.com>
To: buddy@gmail.com
Subject: Urgent! Verify your account now or risk suspension

Dear user,

We have detected unusual activity in your facebook account. Please verify your identity immediately by clicking the link below:

https://www.facebook.com.secure-verify-login-update-userportal.com

Failure to do so within 24 hours will result in account suspension.

Thank you,
Facebook Security Team

# Phishing Indicators Found:

Fake sender domain: The domain facebooksecure-support.com is not an official Facebook domain.
Urgent and threatening tone: "Verify your account now or risk suspension" pressures the user into fast action.
Suspicious link: The visible link includes "facebook.com" but actually leads to a deceptive phishing URL.
Lack of personalization: No mention of user's name or account details.
Grammar & format issues: Generic closing, poor structure.

# Header Analysis Results (Tool using MXToolbox)

SPF: Fail (the sender is not authorized to send on behalf of Facebook)
DKIM: Fail
DMARC: None
Origin IP: Unknown / suspicious region
Reply-To: Hidden or mismatched

# Conclusion

This email contains multiple phishing traits and is intended to deceive users into clicking a malicious link. It should be reported and blocked. Tools like email header analyzers assist in verifying suspicious communications. Identifying and reporting phishing emails through header and body analysis.
