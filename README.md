## 🔄 DJANGO WEBSITE HOSTING WITH EC2 INSTANCE (AWS)

🐍 (Python),🌐 (Web),📦 (Package),⚙️ (Gear),🔧 (Wrench),🔥 (Fire, for exciting features)
🖥️ (Computer),📈 (Graph, for analytics),💻 (Laptop),📚 (Books, for documentation)

### 🌟 **Step-by-Step Breakdown** 🌟

1. **🔄 Update the System Packages**
   ```
   sudo apt update -> sudo apt upgrade
   ```
   - **Purpose**: Keep your system packages up-to-date 🛠️.
   - **Commands**: 
     - `sudo apt update` 📦 Refreshes the package list.
     - `sudo apt upgrade` 🚀 Upgrades all installed packages.

2. **🔗 Clone the Repository**
   ```
   git clone -> url -> username -> password
   ```
   - **Purpose**: Clone your project repository from GitHub 💻.
   - **Command**: 
     - `git clone <repository-url>` 
     - Enter your **username** 👤 and **password** 🔐 if prompted (for private repositories).

3. **📁 Navigate and List Directory**
   ```
   ls -> cd -> cd -> ls
   ```
   - **Purpose**: Move between directories and check their contents 🗂️.
   - **Commands**: 
     - `ls` shows the files in the current folder 👀.
     - `cd` moves you into the appropriate folder 📂 until you reach the desired project.

4. **🧹 Clean Old Files**
   ```
   rm -rf
   ```
   - **Purpose**: Delete unnecessary files or folders 🗑️.
   - **Command**: 
     - `rm -rf <folder-name>` ⚠️ Use with caution! This will permanently delete the specified directory and its contents.

5. **🛠️ Create a Virtual Environment**
   ```
   cd .. /clear -> Create a virtual environment
   ```
   - **Purpose**: Set up an isolated environment to manage your project’s dependencies 🧪.
   - **Command**: 
     - `python3 -m venv <env-name>` creates the virtual environment.
   - Use `cd ..` to go back and `clear` to clean the terminal screen for a fresh start.

6. **🔧 Install pip (if not already installed)**
   ```
   sudo apt install pip
   ```
   - **Purpose**: Install Python's package manager, `pip` 🐍.
   - **Command**: 
     - `sudo apt install python3-pip`

7. **⚙️ Install `virtualenv` using pip**
   ```
   sudo pip install virtualenv
   ```
   - **Purpose**: Install `virtualenv` to create isolated Python environments 🏗️.
   - **Command**: 
     - `sudo pip install virtualenv`

8. **🔨 Create a Virtual Environment**
   ```
   virtualenv env
   ```
   - **Purpose**: Create a fresh environment to work in 🧑‍💻.
   - **Command**: 
     - `virtualenv <env-name>`

9. **🚀 Activate the Virtual Environment**
   ```
   source env/bin/activate
   ```
   - **Purpose**: Turn on your virtual environment 🟢.
   - **Command**: 
     - `source env/bin/activate` (Linux/macOS) or `.\env\Scripts\activate` (Windows).

10. **📦 Navigate to the Django Package**
    ```
    cd then! Django Package
    ```
    - **Purpose**: Move to the directory containing the Django project 🔍.
    - **Command**: 
      - `cd <Django-folder>`

11. **📥 Install Project Dependencies**
    ```
    pip install -r requirements.txt
    ```
    - **Purpose**: Install the dependencies needed for the project 📜.
    - **Command**: 
      - `pip install -r requirements.txt`

12. **📋 Check Installed Packages**
    ```
    pip list
    ```
    - **Purpose**: List all installed packages within the virtual environment 📝.
    - **Command**: 
      - `pip list`

13. **🔓 Allow Firewall Port**
    ```
    sudo ufw allow 8000
    ```
    - **Purpose**: Open port 8000 to allow traffic for Django’s development server 🚪.
    - **Command**: 
      - `sudo ufw allow 8000`

14. **🚀 Run the Django Development Server**
    ```
    python3 manage.py runserver 0.0.0.0:8000
    ```
    - **Purpose**: Start your Django server and make it accessible at `0.0.0.0:8000` 🌍.
    - **Command**: 
      - `python3 manage.py runserver 0.0.0.0:8000`

---

### 🌐 **About the Website: [http://3.7.45.96:8000/index](http://3.7.45.96:8000/index)**

Once you have followed the steps above and the server is running, you can visit the **Django-powered website** at the address:

**🔗 [http://3.7.45.96:8000/index](http://3.7.45.96:8000/index)**(This service are paid hence are not hosted for long time you can check) the video

- **What is this site?**  
  This is a Django web application, likely containing an index page or homepage where users can interact with content. The structure and content of the site can vary depending on your project. The `index` route typically shows the main landing page of the site.
  
- **How to interact with the site?**  
  Once you visit the site, you can navigate through the links, forms, and any interactive elements presented on the page. The website may display dynamic data processed by the Django backend, providing functionality like form submissions, user authentication, or data visualization.

- **Port 8000**: This is the default port used for Django development servers. Your site will be accessible via this port unless you modify it in the command.

For more help or troubleshooting, feel free to refer to the [Video Tutorial](https://drive.google.com/file/d/1dfQ08o6NICuWllxNjvOf7Sj5Yu6SHg0d/view?usp=sharing) 📹.

---

Let me know if you have any more questions! 👋
