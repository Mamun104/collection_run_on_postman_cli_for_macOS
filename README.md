# 🚀 Collection Run on Postman CLI for macOS

## 📌 Technology & Tools Used
- 🛠 **Postman** – API testing tool
- 📝 **Visual Studio Code** – Code editor
- 💻 **Terminal** – Command-line interface

---

## ✅ Prerequisites

Before starting, ensure you have the following installed:

- ✅ **Postman** installed on your system – [Download Here](https://www.postman.com/downloads/)
- ✅ **Postman CLI** installed

---

## 🌟 Project Scenario

This project focuses on performing CRUD (Create, Read, Update, Delete) operations via APIs using Postman CLI:

1️⃣ Create a new user
2️⃣ Create a user with ID and Name
3️⃣ Retrieve all users
4️⃣ Get a user by ID
5️⃣ Update a user by ID
6️⃣ Delete a user by ID

🔗 **API Documentation**: [Click Here](https://documenter.getpostman.com/view/16548351/2s9Y5SWRC4)

---

## 🤔 What is Postman CLI?

Postman CLI (Command Line Interface) allows developers to run Postman collections from the terminal. It’s useful for:
- ✅ Automating API tests
- ✅ Integrating API testing into CI/CD pipelines
- ✅ Running scheduled API monitoring

---

## 📖 Step-by-Step Guide

### 🔹 Step 1: Set Up Postman

1. **Open Postman** 📨
2. **Create a workspace** 🏢
3. **Create a collection** 📂

### 🔹 Step 2: Configure the Collection for CLI

1. **Click on your collection** 📁
   
   ![Collection Click](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/5ae3cde3-e3f8-492b-8ad8-58fb800a7fd9)

2. **Click on the "Run" button** ▶️

   ![Run Button](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/6ee1dab5-47e6-4fb8-87f5-d314543fa1fc)

3. **Click "Automate run via CLI"** 🏃‍♂️

   ![CLI Run](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/2197efd6-e3ad-4022-ab71-02a7bb470b7c)

---

### 🔹 Step 3: Install Postman CLI

📌 Open the terminal and run:

```sh
curl -o- "https://dl-cli.pstmn.io/install/osx_64.sh" | sh
```

✅ Postman CLI will be installed successfully!

---

### 🔹 Step 4: Generate API Key

1. Open **Postman** → Go to **Settings** → Select **Postman API Keys** 🔑
2. Click **"Add API Key"** ➕
3. Copy the generated API key 📋

![API Key](https://github.com/Mamun104/collection_run_on_postman_cli_for_macOS/assets/78067017/adf76bed-5cb2-434f-a9fb-8c82823c79c2)

---

### 🔹 Step 5: Log in to Postman CLI

Run the following command and replace `{{xyz}}` with your API key:

```sh
postman login --with-api-key {{xyz}}
```

✅ If login is successful, you’ll see a confirmation message.

---

### 🔹 Step 6: Run the Collection

Execute the collection with the command below, replacing `{{collection_key}}` with your collection key:

```sh
postman collection run {{collection_key}}
```

🎯 This will run all requests in the collection and display the results in the terminal!

---


