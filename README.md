# 🎵 Music Data Insights (PostgreSQL Project)

This project, **Music Data Insights**, is a relational database built using **PostgreSQL** and managed through **pgAdmin 4**.  
It models a **digital music store** and allows users to run analytical SQL queries to explore insights about customers, artists, playlists, and sales data.

---

## 🗺️ Database Schema
Below is the Entity Relationship Diagram (ERD) showing how all tables are connected:

[Database Schema]

<img width="594" height="598" alt="schema_diagram" src="https://github.com/user-attachments/assets/033a9bc1-43bc-4019-b79b-7049bf6a2cda" />


*(The diagram illustrates the relationships between Album, Artist, Track, Playlist, Customer, Invoice, and other tables.)*

---

## 🧰 Tools & Technologies

- **PostgreSQL 17**
- **pgAdmin 4**
- **SQL (DDL & DML)**
- **CSV Data Imports**

---

## 🗂️ Database Overview

The project simulates a digital music store database containing tables for albums, artists, customers, employees, invoices, playlists, and more.  
It’s designed to perform both **data manipulation (DML)** and **data definition (DDL)** operations, along with queries for generating business insights.

### 📋 Tables Used

| Table Name | Description |
|-------------|--------------|
| `album` | Stores album details including title and artist reference |
| `artist` | Contains artist information |
| `customer` | Customer details such as name, contact, and support rep |
| `employee` | Employee and support representative information |
| `genre` | Defines music genres |
| `invoice` | Customer billing information |
| `invoice_line` | Individual items within an invoice |
| `media_type` | Media file types (e.g., AAC, MPEG) |
| `playlist` | Stores playlist names |
| `playlist_track` | Maps playlists to tracks |
| `track` | Details of each music track (title, composer, album, etc.) |

---

## ⚙️ Setup Instructions

1. **Install PostgreSQL (v17 or higher)**  
2. **Open pgAdmin 4**
3. Create a new database:
   ```sql
   CREATE DATABASE music_database;
   ```
4. Create the tables using SQL scripts:
   ```sql
   CREATE TABLE artist (...);
   CREATE TABLE album (...);
   CREATE TABLE track (...);
   ```
5. Import data from CSV files into each table:
   ```sql
   \copy table_name FROM 'path_to_your_file.csv' DELIMITER ',' CSV HEADER;
   ```

---

## 🧠 Key Learnings

- Designed and implemented a **relational database schema** using PostgreSQL.  
- Established **primary and foreign key relationships** across 11 interrelated tables.  
- Imported, validated, and cleaned large CSV datasets.  
- Applied **SQL aggregate functions**, joins, and grouping for data insights.  
- Strengthened understanding of **data modeling** and **query optimization**.

---

## 👨‍💻 Author

**Name:** Souvik Bose  
**Project:** [music-data-insights](https://github.com/yourusername/music-data-insights)  
**Tools Used:** PostgreSQL | pgAdmin 4  

If you found this project useful, feel free to ⭐ star the repository or connect with me on [LinkedIn](https://www.linkedin.com/in/souvik-bose-7272ab1b3/). 

---

## 🚀 Future Enhancements

- Add **ER Diagram** for visualizing database relationships.  
- Build **SQL Views** to simplify analytical reporting.  
- Create **Stored Procedures and Triggers** for automation.  
- Integrate with **Power BI or Tableau** for data visualization.  
- Add **Python or Streamlit dashboard** for interactive insights.  

---
