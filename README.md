# Mitigating Fraudulent Emails at Contoso

## Introduction
Fraudulent emails, such as phishing attacks, pose significant risks to organizations,leading to data breaches, data theft, and financial losses,Malware Infection,Loss of Trust **Contoso's** email system is currently vulnerable to fraudulent emails.

## Solution Overview
To mitigate Fraudulent emails,I will recommend the purchase of;
**Microsoft 365 E5**: This is the most robust plan, providing advanced threat protection (ATP), Defender for Office 365, advanced auditing, and security monitoring.

 **Features to Mitigate the Fraudulent Email Concern**

 Anti-Phishing & Anti-Spam & Anti -Malware Policies – Policies in Microsoft Defender for office 365 to detect and block phishing attempts.

 Safe Links – Protect from opening and sharing malicious links in email messages 

 Set up DMARC to specify how email servers should handle messages that don’t pass SPF/DKIM checks.

 Zero-Hour Auto Purge (ZAP) – Automatically removed phishing emails post-delivery.

 Safe Atttachements - Protect from malicious content in email attachments and files.
 
 ### Step 1: Configure Anti-Phishing Policies in Defender for Office 365**
To do that:

- I went to **Microsoft Admin page** https://admin.microsoft.com/?login#/homepage

- Sign in my Microsoft Admin Security ID.
  
- Navigate to **Security** **Email & Collaboration** > **Policies & Rules** > **Threat Policies** > **Anti-Phishing**.

- Create policy name. In this case, I used **Anti-Phishing**

- **Added protected user, domains**.

- **Enable intelligence impersonation protection,mailbox intelligence, spoof intelligence**.

- **Reviewed the policy and then clicked on Done to apply the policy**.

<img width="960" alt="Email 1" src="https://github.com/user-attachments/assets/616e7f5d-fd8a-4ba4-ac54-348c7d27fbf8" />

### Step 2: I created an Anti-Spam policy

- I went to **Microsoft Admin page** https://admin.microsoft.com/?login#/homepage

- Sign in my Microsoft Admin Security ID.
 
- Navigate to **Security** **Email & Collaboration** > **Policies & Rules** > **Threat Policies** > **Anti-Spam**
 
- Create policy name. In this case, I used **Denis Anti-spam inbound policy**


- **Added protected user**

<img width="951" alt="email 5" src="https://github.com/user-attachments/assets/b1861bef-f556-4bc7-8061-d99c71ba7a77" />

### Step 3: I created an Anti-Malware policy

- I went to **Microsoft Admin page** https://admin.microsoft.com/?login#/homepage

- Sign in my Microsoft Admin Security ID.

- Navigate to **Security** **Email & Collaboration** > **Policies & Rules** > **Threat Policies** > **Anti-Malware**

- Create policy name. In this case, I used **Anti-Malware**

**Added protected user**

**Enable zero-hour auto purge for malware**

<img width="952" alt="email 2" src="https://github.com/user-attachments/assets/065bcce9-0dba-4f41-aa80-9da8e6a91f3b" />

### Step 4: I created a Safe Attachment policy**

- I went to **Microsoft Admin page** https://admin.microsoft.com/?login#/homepage

- Sign in my Microsoft Admin Security ID.

- Navigate to **Security** **Email & Collaboration** > **Policies & Rules** > **Threat Policies** > **Safe Attachment policy**

- Create policy name. In this case, I used **Safe Links and Safe Attachments**

**Added protected user**

- Configure **Block current and future messages and attachments with detected malware**.

  <img width="945" alt="email 3" src="https://github.com/user-attachments/assets/5999e893-651a-4662-a396-c0e3622c78b3" />

  ### Step 5: I created a Safe Link policy**

- I went to **Microsoft Admin page** https://admin.microsoft.com/?login#/homepage

- Sign in my Microsoft Admin Security ID.

- Navigate to **Security** **Email & Collaboration** > **Policies & Rules** > **Threat Policies** > **Safe Link policy**

- Create policy name. In this case, I used **Denis Safe Links policy**


**Added protected user**

- Apply **Safe Links to email messages sent within the organization**

  <img width="960" alt="email 4" src="https://github.com/user-attachments/assets/8c2d6359-dc17-4ec1-8eeb-84e12b018a12" />

  **Testing and Deployment**

- To ensure that the new policies function as intended without negatively impacting business operations, they should first be applied to a designated group of test users. This test group should include a mix of standard users as well as VIP users, such as the CEO, CFO, and CISO. Including these key stakeholders will help assess whether the policies are suitable for the entire organization and specifically address the needs of high-priority users. Once the test phase is complete and any necessary adjustments are made, the policies can be rolled out to the broader organization.

**To get the mail flow report**

**Microsoft Admin page** https://admin.microsoft.com/?login#/homepage

Navigate to  **Security** > **Email & collaboration** > **Reports** > **Email & collaboration reports**.

- **View detailed email security reports, including mail flow insights**


**Potential Risks Implementing the policies**


- **Cost**: Microsoft 365 E5 is more expensive compared to other Microsoft 365 plans.

- **Complexity**: The advanced features and configurations may require specialized knowledge and training.

- **User Impact**: Some security measures, such as multi-factor authentication (MFA) and conditional access policies, may impact user experience by adding extra steps to access resources.

 **Conclusion** The implementation of multiple security measures significantly strengthened Contoso's mail system defenses against fraudulent emails. Key actions included configuring Anti-Phishing, Anti-Malware, and Anti-Spam policies, alongside enabling Safe Links and Safe Attachments. These measures created a robust multi-layered defense against domain spoofing and other malicious email threats. Additionally, activating Zero-Hour Auto Purge (ZAP) ensured that phishing emails were swiftly identified and removed, even after delivery, minimizing the potential risks to the organization. To validate these implementations, continuous monitoring and reporting will be conducted to assess their effectiveness and refine the approach as needed.
