# The Suspicious Domain

Still on the very easy stage of HTB OSINT.

**Question 1: What is the registrant's email address from the WHOIS record?**

Here is the WHOIS:

<img width="454" height="902" alt="image" src="https://github.com/user-attachments/assets/d3ebae1a-54bf-4fd1-bad1-ab6c3f6df614" />

It is stated that the registrant contact is Alex Morgan

**Answer: Alex Morgan**

**Question 2: What is the complete phone number including country code?**

Still on the WHOIS

**Answer: +1-408-555-0987**

**Question 3: When was the domain created? (Format: YYYY-MM-DD)**

Still on the WHOIS (Creation Date: 2024-01-20)

**Answer: 2024-01-20**

**Question 4: What is the exact organization name from WHOIS?**

Still on the WHOIS (Organization: Morgan Tech Reviews LLC)

**Answer: Morgan Tech Reviews LLC**

**Question 5: What city is listed in the registrant's address?**

Still on the WHOIS (Registrant Contact -> City: San Jose)

**Answer: San Jose**

**Question 6: What is the domain's transfer status?**

This one is a little harder as I had to look up examples of transfer statuses.

It is still on the WHOIS (Domain Status: clientTransferProhibited)

**Answer: clientTransferProhibited**

**Question 7: What company is being targeted?**

From the hosting details:

<img width="1547" height="525" alt="image" src="https://github.com/user-attachments/assets/8868d4f0-8d31-4e37-91d7-b8c8390a15c0" />

The Digital Fingerprint shows the Google Analytics ID

**Answer: TechFlow**

**Question 8: What email service is the threat actor using?**

The threat analysis shows the information about the potential attack.

<img width="1535" height="441" alt="image" src="https://github.com/user-attachments/assets/eb6cd4f5-fa3a-411c-a4a7-1defa6345d40" />

**Answer: tempmail**

**Question 9: How many GitHub Pages IPs are configured?**

The DNS records shows 4 A records with 4 GitHub pages

<img width="1531" height="490" alt="image" src="https://github.com/user-attachments/assets/ec3ff44c-5822-45e5-8928-5ab3541d9ccc" />

**Answer: 4**

### Flag

HTB{alexmorgantempmailcom_20240120_morgantechreviewsllc}

CTF Solved. Flag captured.
