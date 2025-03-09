Crowdfunding Platform 🚀

Introduction

This is a crowdfunding platform where users can discover and support various campaigns by making donations. Payments are securely processed through the PayTM gateway, ensuring both transparency and the option for anonymous contributions.

Features 🎯

User Features

Browse active campaigns directly from the homepage.

Click on a campaign to view detailed information.

Contribute to a cause via PayTM.

Share campaigns with others to increase visibility.

View transaction details under the campaign’s donation list (with anonymity maintained).

Reach out through the 'Contact Us' form for any inquiries.

Admin Features

Access all user features.

Launch new campaigns by adding details such as title and funding goal.

Disable campaigns once the objective is met or as needed.

Update ongoing campaign details (excluding the raised amount).

Assign new admins if required.

Database Operations

Users can perform Create, Read, Update, and Delete (CRUD) operations on database records as necessary.

Note: A default admin is set up, and the login route is not publicly visible in the UI. Admins can access it via website_url/admin/login using their credentials. This prevents unnecessary login options for users only interested in donations.

Technology Stack 🛠️

The platform is built using the MERN stack:

React.js

Node.js

Express.js

MongoDB Atlas

API Integration 🌐

PayTM API

Core Components

Secure payment processing via PayTM.

High-performance, schema-less database powered by MongoDB.

Project Motivation

This project was created as part of edunet virtual internship. We aimed to develop a real-world solution for transparent and efficient crowdfunding. . Our goal was to create an intuitive, user-friendly platform that ensures transparency and security in transactions.

Deployment

The platform is live on Vercel: Crowdfunding Platform

Installation Guide

Prerequisites

Ensure you have:

Node.js & npm installed

MongoDB URI

PayTM credentials

create-react-app

Backend Setup

Navigate to the backend directory.

Install dependencies: npm install.

Configure environment variables using the env-sample file.

Start the backend server: node server.js.

Frontend Setup

Navigate to Frontend/crowd-funding-frontend.

Install dependencies: npm install.

Add the backend URL in config.js.

Start the frontend: npm start.

Your app will now be running on port 3000. 🎉

Screenshots

Homepage



Ongoing Campaigns Section:


Campaign Details



Donor List (Transaction IDs partially hidden for security):


Quick Donate & Share Options



Campaign Overview



Admin Login



Admin Dashboard

Admin panel displaying feedback and campaign management.


About Us Page



Contact Us Page



Footer Section

