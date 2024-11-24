# Cloud-Storage-Security-Check
The **CloudStorageSecurity.exe** is the security check tool for HTTP POST credentials and STS temporary upload credentials in Amazon S3 and Alibaba Cloud OSS on GitHub This tool enables website developers to detect and discover possible vulnerabilities in the website's use of cloud storage services. 

## Usage
Double-click the program to run, and access http://127.0.0.1:8000 through the browser. Enter the HTTP/HTTPS request message for requesting STS temporary upload credentials in the page request input box. After CloudStorageSecurity obtains the STS temporary upload credentials, it analyzes the credential policy and reports potential security issues.

https://github.com/user-attachments/assets/5d33950d-ba6a-4a83-95f9-20111a983887

You can find more details about the new type of vulnerability detection methods in scenarios where users directly upload files to cloud storage services in our research paper **Understanding the Security Risks of Websites Using Cloud Storage for Direct User File Uploads**.

## Exploitation Example
The file overwrite vulnerability can be used to replace files uploaded by other users in SmallPDF, such as replacing the original file content "123" with "456".

https://github.com/user-attachments/assets/e6a98ab3-683a-4bb5-a9b7-0c0fe12e7273
