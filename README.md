# serverless-text-to-speech-engine
Cloud-native, serverless Text-to-Speech engine built using AWS Polly, Lambda, and S3.


**🎙️ Mr.Translator – Serverless Text‑to‑Voice Engine**


 **📌 Project Overview**

Mr.Translator is a serverless text‑to‑speech engine built using AWS Polly, AWS Lambda, and Amazon S3. The system automatically converts uploaded text files (.txt) into high‑quality MP3 audio using AI‑powered neural voices.

This project demonstrates how cloud‑native and AI services can be combined to build scalable, event‑driven voice applications with zero server management.


**🧠 Working Mechanism**

A .txt file is uploaded to the source S3 bucket

S3 event triggers an AWS Lambda function

Lambda reads the text file

Amazon Polly (AI service) converts text into speech

Generated .mp3 file is stored in the destination S3 bucket

This entire flow is fully automated and serverless.




**🛠️ Architecture**

<img width="2208" height="1164" alt="image" src="https://github.com/user-attachments/assets/d9f1cdd5-d4eb-452f-a234-282f9a48c95f" />



<img width="1920" height="1080" alt="Screenshot from 2026-01-14 01-52-16" src="https://github.com/user-attachments/assets/21ac48a1-241d-4478-b0fd-1c320ff470e2" />





**📦 Tech Stack**

    AWS Lambda (Python)
    Amazon Polly
    Amazon S3
    boto3
    IAM	Secure service permissions


**📚 Real‑World Use Cases**

Voice narration for blogs & articles

Accessibility for visually impaired users

Audio generation for e‑learning platforms

Voice features for cloud applications

Automated audiobook creation


👤 Author

Karthik
Cloud & DevOps Enthusiast
