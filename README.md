# AI-Powered-IT-Helpdesk-Chatbot-Showcase
Showcasing an AI-Powered IT Helpdesk Chatbot built with RASA. It automates IT support, delivering quick responses to user queries. Due to confidentiality, the code is not shared, but screenshots highlight its features.

# Axpert License Management System

This system streamlines the process of issuing, renewing, modifying, reactivating, and tracking Axpert licenses. It also provides an FAQ section, user-specific query handling, and a resource download section, enhancing user support and operational efficiency.

## Features

### 1. Issue New Axpert License
- Users can submit a new license request form, providing details such as:
  - **Customer Name**
  - **Partner Name**
  - **Email**
  - **Number of Users & Developers**
  - **Remarks**
  - **License Type & Version Preferences**
- The system confirms submission and securely stores user details in a PostgreSQL database.
- Upon approval, the license issuing team sends the license via email.

### 2. Renew Axpert License
- Users can request license renewal by submitting their **License Number**.
- The system verifies the current license status and expiration date.
- User information is stored securely in a PostgreSQL database, enabling the renewal team to process renewals efficiently.

### 3. Modify Axpert License
- Users can request modifications to their existing license, such as adding users or developers.
- The form requires:
  - **Current Number of Users**
  - **Number of Users to Add**
- Details are stored in the database, and requests undergo an approval process before the license is updated.

### 4. Reactivate Axpert License
- Users can initiate reactivation of a deactivated license by providing:
  - **MAC ID**
  - **License Number**
- The system verifies the user's identity and license details before reactivation.

### 5. Track License Details
- Users can view detailed information about their Axpert license, including:
  - **Username**
  - **License Issue & Expiration Dates**
  - **License Types**
  - **Version Details**
  
### 6. Frequently Asked Questions (FAQs)
- FAQs are categorized into seven different categories for easy navigation.
- Users can search the FAQ database using keywords with fuzzy matching.
- The system displays relevant questions and answers based on the search query.

### 7. New Chat - User-Specific Questions
- The system uses a BERT-base model to analyze semantic similarity between user queries and prestored FAQ database entries.
- It calculates similarity scores and retrieves responses such as tutorial videos or text-based explanations based on the highest similarity score.

### 8. Resource Download Section
- The system categorizes resources, such as:
  - **Setup Kits**
  - **Patch Releases**
  - **Axpert Binaries** for different software versions
- Users can navigate to a specific category to access relevant download links.

---

This system is designed to enhance user experience by providing quick access to essential license management features, support resources, and detailed information retrieval.

## Screenshots

### Chatbot Interaction
Here are some outputs from the chatbot showcasing its capabilities:

<div align="center">

| License Request Form | Track License Details |
| --- | --- |
| <img src="images/Main%20Menu.png" alt="License Request Form" width="400"> <br> License Request Form | <img src="images/Main%20Menu.png" alt="Track License Details" width="400"> <br> Track License Details |

</div>

<div align="center">

| Modify License | Reactivate License |
| --- | --- |
| <img src="images/Main%20Menu.png" alt="Modify License" width="400"> <br> Modify License | <img src="images/Main%20Menu.png" alt="Reactivate License" width="400"> <br> Reactivate License |

</div>

<div align="center">

| New License Confirmation | Renew License Confirmation |
| --- | --- |
| <img src="images/New%20license%20Confirmation.png" alt="New License Confirmation" width="400"> <br> New License Confirmation | <img src="images/Renew%20license%20Confirmation.png" alt="Renew License Confirmation" width="400"> <br> Renew License Confirmation |

</div>

<div align="center">

| New Chat | New Chat |
| --- | --- |
| <img src="images/Newchat2.png" alt="New Chat" width="400"> <br> New Chat | <img src="images/NewChat3.png" alt="New Chat" width="400"> <br> New Chat |

</div>

<div align="center">

| New Chat | FAQs Menu |
| --- | --- |
| <img src="images/Newchat4.png" alt="New Chat" width="400"> <br> New Chat | <img src="images/FAQs%20Menu.png" alt="FAQs Menu" width="400"> <br> FAQs Menu |

</div>

<div align="center">

| Common Axpert FAQs Sub Menu | Limit Exceeded FAQs Sub Menu |
| --- | --- |
| <img src="images/Common%20Axpert%20FAQs%20Sub%20Menu.png" alt="Common Axpert FAQs Sub Menu" width="400"> <br> Common Axpert FAQs Sub Menu | <img src="images/Limit%20Exceeded%20FAQs%20Sub%20Menu.png" alt="Limit Exceeded FAQs Sub Menu" width="400"> <br> Limit Exceeded FAQs Sub Menu |

</div>

<div align="center">

| FAQs Answers - “How to ?” | Watch Tutorial Videos |
| --- | --- |
| <img src="images/FAQs%20Answers%20-%20“How%20to%20”.png" alt="FAQs Answers - “How to ?”" width="400"> <br> FAQs Answers - “How to ?” | <img src="images/Watch%20Tutorial%20Videos.png" alt="Watch Tutorial Videos" width="400"> <br> Watch Tutorial Videos |

</div>

<div align="center">

| Watch Tutorial Videos | Download Resources Sub Menu |
| --- | --- |
| <img src="images/Watch%20Tutorial%20Videos2.png" alt="Watch Tutorial Videos" width="400"> <br> Watch Tutorial Videos | <img src="images/Download%20Resources%20Sub%20Menu.png" alt="Download Resources Sub Menu" width="400"> <br> Download Resources Sub Menu |

</div>

<div align="center">

| Download Setup Kits | Download Axpert Binaries |
| --- | --- |
| <img src="images/Download%20Setup%20Kits.png" alt="Download Setup Kits" width="400"> <br> Download Setup Kits | <img src="images/Download%20Axpert%20Binaries.png" alt="Download Axpert Binaries" width="400"> <br> Download Axpert Binaries |

</div>
