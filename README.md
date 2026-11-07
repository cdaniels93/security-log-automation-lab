# Security Log Collection and Analysis Automation

This lab explored how security teams collect and review computer activity records called logs.

## Manual Linux log review

I used Linux commands to find failed password attempts, extract and count their source IP addresses, and identify IPs with more than five attempts. The sample contained 15 failed attempts. The most frequent source was `192.168.1.100`, with 9 attempts.

![Kali terminal showing failed-login analysis](01-linux-log-analysis.png)
