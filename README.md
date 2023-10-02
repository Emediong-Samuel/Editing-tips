# A Technical Writing Editing Checklist

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description

This repository contains a PHP web application that displays an editing checklist for technical writing. The checklist includes essential tips and guidelines for technical writers to enhance the quality of their writing. Users can click through the checklist to access each tip along with an explanation.

## Installation

To run this PHP web application locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Emediong-Samuel/Editing-tips

**Navigate to the project directory**:
```
cd Editing-tips/myphpapp
```
Configure and start your local web server. You can also use tools like **XAMPP**, **WAMP**, or **PHP's built-in server**.

**Access the application in your web browser at**:
```
http://localhost/your-web-app-folder/your-page-name.php
```
(You can use "localhost" or replace it with your server's IP address alongside the correct path to your target PHP file)

## Using XAMPP?
To use XAMPP, follow the directives below.

**Download the XAMPP installer**:
```
wget "https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/8.2.4/xampp-linux-x64-8.2.4-0-installer.run"
```
**Make the Installer Executable** (if needed):
```
chmod +x xampp-linux-x64-8.2.4-0-installer.run
```
**Run the Installer**:
```
sudo ./xampp-linux-x64-8.2.4-0-installer.run
```
Follow the on-screen instructions to complete the installation. You can typically choose the default settings unless you have specific requirements.

**Start XAMPP**:
```
sudo /opt/lampp/lampp start
```
#This command will start the XAMPP services, including Apache (webserver) and MySQL (database server).

**From the "myphpapp" directory, Move the "index.php" file to the correct location within /opt/lampp/htdocs/ :**
```
sudo mv index.php /opt/lampp/htdocs/
```
**Change to the XAMPP directory and restart Apache:**
```
cd /opt/lampp/
sudo ./xampp reloadapache
```
**The web application can now be accessed using the following URL**:
```
http://localhost/index.php
```
#Replace **"localhost"** with your server IP if you're using a remote server.
**NOTE**: If your PHP file is located in a different path or directory, update the URL accordingly to reflect the correct file location.

## How to Use
Navigate through the checklist by clicking the **"Next Tip"** button to reveal the associated editing tips and explanations. Explore the valuable technical writing guidelines to improve your writing skills.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository.

Create a new branch for your feature or bug fix.

Make your changes and commit them with descriptive messages.

Push your branch to your fork.

Submit a pull request to the main repository.
