
# Personal Data Download



As a part of GDPR compliance, ERPNext has Personal Data Download.


Personal data download tool enables a user to automatically download all the personal data they have generated while using ERPNext. This includes personally identifiable data from your user account like: username, full name, birth date, phone numbers, mobile numbers, location, interests, bio, email signature, Email, Contact, Address, Communication, etc. It also includes data from Leads and Opportunities, the details you have saved like phone numbers, mobile numbers, fax, website, and name.


## 1. How to request user data download


1. To begin downloading data, the user has to **logged in** and visit [host-name]/request-data (e.g. erpnext.com/request-data) in the URL field.


![Request Data](/files/request-data-webform.png)
2. After submitting your request, you will receive a success response.
![Request Data](/files/download-request-succes.png)
3. This will send an email with a download link of the data to the email address associated with the user.
![Download Data Email](/files/download-data-email.png)


The file available for download will be in the JSON format.


## 2. Personal Data Download Request DocType


The request is also recorded in the DocType "Personal Data Download Request", the file-link that is sent to the user via email is also attached to the doc. Search for Personal Data Download Request from the search bar.


![Personal Data Download Request Doctype](/files/personal-data-download-request-doctype.png)


### 3. Related Topics


1. [Personal Data Deletion](/docs/en/setting-up/personal-data-deletion)




