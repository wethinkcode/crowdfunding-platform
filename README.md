# Crowdfunding-Platform
Repository for the local development of WeThinkCode's crowdfunding platform.

## Repository Content
- **/wp-content**: Contains the plugins and themes needed to create the site
- **.gitignore**
- **README.md**

## Requirements
Before cloning this repository, ensure the following are installed:
- [WordPress](https://wordpress.org/download/)
- [XAMPP Control Panel](https://www.apachefriends.org/download.html)

## Installation and Setup

### 1) XAMPP
- Install and run **XAMPP**.
- Start **Apache** and **MySQL** from the XAMPP Control Panel.
- Open your browser and go to `http://localhost/phpmyadmin/`.
- Once the page is loaded, click **New** and enter a database name to create a new database.

### 2) WordPress
- Extract **WordPress** into `C:\xampp\htdocs\` and rename it to `crowdfunding-platform`.
- Open the folder in your browser (url: http://localhost/crowdfunding-platform/)
- Follow the installation instructions and enter the following information where relevant:
	- Database Name: ```The name of the database you created```
	- Username: ```root```
	- Password: ```“”``` (leave empty)
	- Database Host: ```localhost```

### 3) GitHub repository
- Open a terminal in **XAMPP**’s htdocs folder (`C:\xampp\htdocs\`).
- Run the following command:

```bash
git clone git@github.com:wethinkcode/crowdfunding-platform.git wp-content
```
- Then navigate to the repository that has been cloned

```bash
cd wp-content
```