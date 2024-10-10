## Exercise_10-Email Automation-send_email
## Aim:
To automate the process of sending an email using UiPath Studio.

## Equipment Required:
UiPath Studio installed on your computer.
Email Account (e.g., Gmail, Outlook) with necessary credentials.
SMTP, IMAP, or Outlook Integration (depends on your email provider).
Computer with:
Minimum 4 GB RAM.
Minimum 2.0 GHz CPU.
Windows operating system.

## Procedure:
## Create a New Process in UiPath Studio:
Open UiPath Studio and create a new project by selecting Process under the New Project tab.
Name the process (e.g., Email Automation) and click Create.

## Add Email Activities Package:
In the Manage Packages panel (top ribbon), click on Manage Packages.
Search for UiPath.Mail.Activities and install the package. This allows you to use email-related activities
like sending and receiving emails.

## Choose an Email Activity: Depending on the type of email provider you're using, select the appropriate activity:
SMTP (Simple Mail Transfer Protocol): For sending emails.

## Send Email Using SMTP (For Gmail/Other Providers): Add SMTP Mail Message Activity
In the Activities panel, search for the Send SMTP Mail Message activity and drag it into your workflow.

# Configure SMTP Server:
In the Properties panel for the activity, configure the SMTP server settings:
Port: For Gmail, use 587.
Server: For Gmail, use smtp.gmail.com.
SecureConnection: Use StartTls for secure connection.

## Configure the Email Parameters:
To: Enter the recipient's email address (e.g., recipient@example.com).
From: Enter the sender's email address (your Gmail address, e.g., youraddress@gmail.com).
Subject: Enter the subject of the email (e.g., Test Email from UiPath).
Body: Enter the email body content (e.g., Hello, this is an automated email from UiPath.).
Attachments (Optional): If you want to attach a file, provide the file path in the Attachments property.

## Set Authentication:
You need to authenticate the email sending by providing your username (Gmail address) and
password in the Properties panel under the Username and Password sections.

## Save and Run the Workflow:
Press CTRL+S to save the workflow.
Click the Run button in UiPath Studio to execute the automation
The email will be sent automatically using either SMTP or Outlook, depending on the chosen activity.

## Output:
![Screenshot 2024-09-27 192351](https://github.com/user-attachments/assets/7951e4db-c084-4001-8c5b-e1882b348919) 
![Screenshot 2024-09-27 192410](https://github.com/user-attachments/assets/37caacdb-aceb-4aef-a202-f3dc1ce5670f)
![Screenshot 2024-09-27 205823](https://github.com/user-attachments/assets/640f8b14-a857-487c-8526-b9709af00acd)
![Screenshot 2024-09-27 205849](https://github.com/user-attachments/assets/60707272-824e-4c63-b8f7-2cd17a4c7fba)
![Screenshot 2024-10-10 095024](https://github.com/user-attachments/assets/b0664e67-d6bf-43c7-b948-3678b4b56a5f)
![image](https://github.com/user-attachments/assets/d50ed55e-41db-49dc-b004-a1195ec62c19)
![image](https://github.com/user-attachments/assets/d93f4ae6-e177-4173-b244-e77950a2fa6e)

## Result:
The email is successfully sent to the recipient using the configured email account and the appropriate
activity (SMTP).





