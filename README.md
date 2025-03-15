# Social-Media-Database
This project features a **relational database** implemented in **Microsoft SQL Server**, designed for a social media platform. The database includes structures for users, their posts, and other activity types characteristic of a modern social network. The implementation contains **triggers, procedures, and functions** to ensure the correct operation of platform functionalities.  

# Features  
- **User Account Management** – Create, edit, and delete user accounts.  
- **User Activity Management** – Users can:  
  -- Create and manage **posts**  
  -- Add **interests**  
  -- Join and organize **events**  
  -- Manage **friend connections**  
- **Role-Based Access Control (RBAC)** – Three user roles:  
  -- **Administrator** – Full database management access.  
  -- **Moderator** – Ability to moderate content.  
  -- **Regular User** – Standard platform interactions.  
- **Data Browsing with Views** – Simplified data retrieval using predefined **views**.  
- **Stored Procedures & Functions** – Manage data through dedicated **procedures and functions**.  

# Database Setup
### 1. Requirements  
To run this project, you need:  
- **Microsoft SQL Server** (2016 or later recommended)  
- **SQL Server Management Studio (SSMS)** or another SQL client  

### 2. Database Initialization  
To set up the database, execute the provided SQL code inside the code:  

```sql
social_wall_database.sql
```
This code will:
- Create necessary database objects (tables, views, procedures, and triggers).
- Populate the database with sample test data.

### 3. How to Use
Once the database is set up, you can:
- Query data using predefined views for easy data browsing.
- Execute procedures to manage users, posts, and other activities.
- User Activity Tracking – Monitor user interactions, including:  
  -- Post history and engagement (likes, comments, shares).  
  -- Participation in events and group activities.  
  -- Friend connections and interaction frequency.  
