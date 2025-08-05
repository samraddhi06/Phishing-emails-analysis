# Phishing-emails-analysis

Task - 2 Analyze a Phishing Email Sample. 

## Objective

To identify phishing characteristics in a suspicious email sample .

## Features

Email header analysis

Suspicious links and attachments 

Email body content examination

URL and domain analysis

## Sample Analyzed

Sample phishing email analyzed is from https://github.com/rf-peixoto/phishing_pot public repository samle email.

## Tools Used

MX Toolbox Email Header Analysis

EML Analyzer

Virus Total

## Analysis 

Received an email from BANCO DO BRADESCO LIVELO claming that card has amount that expires today.

Email address of sender - banco.bradesco@atendimento.com.br

Sender domain - atendimento.com.br

Email header analysis

<img width="1366" height="341" alt="2025-08-05 (2)" src="https://github.com/user-attachments/assets/c1feb793-3893-4519-8e13-37c6080e02ee" />

IP address of sender - 137.184.34.4

<img width="1259" height="687" alt="2025-08-05" src="https://github.com/user-attachments/assets/79af19b2-3992-4059-bc22-1b2cd63bf526" />

SPF authentication is fail.

<img width="1307" height="489" alt="2025-08-05 (1)" src="https://github.com/user-attachments/assets/6429b3c5-b5f0-4b21-a306-3fae03525a8f" />

Suspicious URL found in email - https://blog1seguimentmydomaine2bra.me/

<img width="1366" height="641" alt="2025-08-05 (3)" src="https://github.com/user-attachments/assets/ca187982-1a43-4080-b6a0-ec2948c5bb48" />

Email analysis by MX toolbox  

<img width="1315" height="652" alt="2025-08-05 (4)" src="https://github.com/user-attachments/assets/269ee33b-5909-4408-b368-9acd5fd51c9c" />
<img width="1366" height="645" alt="2025-08-05 (5)" src="https://github.com/user-attachments/assets/1d76cc08-1830-4bfb-9fa8-a6cad8c5247d" />
<img width="1366" height="655" alt="2025-08-05 (6)" src="https://github.com/user-attachments/assets/9e460a5c-ddf7-4494-8f9f-abc2046eb103" />

## Observation

Malicious IP address detected.
Suspicious URL address.
SPF authentication - Fail.
Email body contain urgent and threatning words to create urgency.

## Conclusion

The email analyzed is a phishing email as malicius ip address, suspicios URL, failed authentication, manipulating words are used. Awareness of phishing emails is crucial to safeguard recipents from phishing attacks.
