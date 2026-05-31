# Kindly

Kindly is a community-based web application designed to connect people who need assistance with individuals who are willing to help within their local community. The platform serves as a space where members can seek helpers for various tasks, offer support, and build meaningful connections through collaboration and service. 

---

# Table of Contents
- Installation
- Usage
- Features
- Screenshots
- Folder Structure
- Developers
- License

---

# Installation

## Requirements
- XAMPP
- PHP
- MySQL
- Web Browser

## Steps to Run

1. Download or clone the repository.
2. Copy the project folder into the `htdocs` folder.
3. Start Apache and MySQL in XAMPP.
4. Open phpMyAdmin.
5. Create a database named:

```plaintext
db_kindly
```

6. Import the provided `.sql` file.
7. Open your browser and type:

```plaintext
http://localhost/Kindly/public
```

---

# Usage

## Your sample user account

Email: jillshanicecascarro16@gmail.com
Password: shanice

Users start with 20 credit points, which are used to request help from others.

## How to Use
Log in using the sample account and navigate through the system using the navigation bar

### If You Are Requesting Help
1. Go to Feed and create a post.
2. Enter the required details: description, date, time, credit points, and optional image.
3. Wait for users to inquire and choose whether to accept or ignore requests.
4. Communicate with the helper through private messages until the work is completed.
5. Once satisfied, open the conversation, click the three dots, and select Mark Transaction as Done. Credit points will automatically transfer to the helper and be deducted from your account.

### If You Are a Helper/Worker
1. Go to Feed and browse available posts.
2. Click/Select the post/task that interests you and either bookmark it or message the requester. (Bookmarked post will appear in your profile under interests)
3. Use private messaging to discuss availability and work details.
4. Once the requester marks the transaction as completed, credit points will automatically be transferred to your account.

### Viewing Transaction History
1. Go to Profile
2. Click Balance
3. View History to see transaction records.


## Your admin account
Email: admin@kindly.com
Password: admin123

## How to use
1. Log in using the admin account.
2. Use the Dashboard to view reports and overall system data.
3. Go to Manage Users to view or delete user accounts.
4. Go to Manage Posts to view or remove community posts.
5. Go to User Credits to gift, deduct, or view users’ transaction history.
6. Check Reports to review user concerns and take necessary action.
7. To export system data, go to Analytics. You may export:
   a. User records only
   b. Post records only
   c. Full system report


---

# Features
Community Filtering
User Authentication
Post Creation
Post Bookmarking 
Direct Messaging
Credit System
Transaction History
Transaction Security
Real-time updates

---

# Folder Structure

```plaintext
Kindly/
├── App/
│   ├── Config/
│   ├── Controller/
│   ├── Models/
│   └── View/
│       └── admin/
│
├── Public/
│   ├── assets/
│   │   ├── css/
│   │   ├── js/
│   │   ├── img/
│   │   │   └── posts/
│   │   └── javascript/
│   │
│   ├── uploads/
│   │   └── Posts/
│   │
│   ├── .htaccess
│   └── index.php
│
├── .gitignore
├── composer.json
└── composer.lock

```

---

# Developers
- Jill Shanice Cascarro
- Edrian Ardeño
- Delight Grace Panganiban
- Shamel Sancho
- Group 9

---

# License

This project is for educational purposes only.

