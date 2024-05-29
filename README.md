

# 📊 Instagram User Data Analytics Project


Welcome to the Project! This project involves performing various SQL queries to extract meaningful insights from a social media platform's user and activity data. By analyzing user behavior and platform engagement, we aim to optimize user experience and enhance service offerings.

## 📋 Project Overview
This project focuses on:
* Identifying key metrics such as longest-tenured users,inactive users, and most popular content.
* Understanding user registration patterns.
* Detecting potential bot accounts.
* Analyzing hashtag usage on the platform.

## 🗂️ Table of Contents

* [Introduction](#heading-1 "Goto Introduction")   
* [Problem Statement](#Problem Statement "Goto Problem Statement")   
* [Summary](#heading-1 "Goto Summary")   
* [Operations Performed](#heading-1 "Goto Operations Performed")   
* [Database Schema](#heading-1 "Goto Database Schema")   

### 🌟 Introduction

In today's data-driven world, understanding user behavior and platform engagement is crucial. This project aims to provide actionable insights through comprehensive SQL queries, enabling better decision-making and strategy optimization.

### 📝 Problem Statement
The primary objective is to analyze user activity and engagement on a social media platform.
* Identify longest-tenured users.
* Find users who have never posted a photo.
* Determine the most liked photo.
* Identify top-used hashtags.
* Analyze user registration patterns.
* Detect potential bot accounts.

### 🧩 Summary
This project involves a series of SQL queries designed to extract and analyze data from the platform's database. The insights derived from these queries provide a comprehensive understanding of user behavior and platform dynamics.



### 🗃️ Database Schema
### Tables Used

      1. users

* id : Unique identifier for each user.
* username : The username of the user.
* created_at : Account creation date and time.


      2. photos

* id :Unique identifier for each photo.
* user_id : ID of the user who posted the photo.
* image_url : URL of the photo.

      3. likes

* photo_id : ID of the liked photo.
* user_id : ID of the user who liked the photo.

      4. tags

* id : Unique identifier for each hashtag.
* tag_name : The name of the hashtag.

      5. photo_tags

* photo_id: ID of the photo associated with the hashtag.
* tag_id: ID of the hashtag.


## 🔗 Links
[![project link](https://img.shields.io/badge/project_link-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.canva.com/design/DAGF4a9pwpM/ZiNOAnhGLuKhHbK0Tiuaew/view?utm_content=DAGF4a9pwpM&utm_campaign=designshare&utm_medium=link&utm_source=editor)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manaschaurasia/)



