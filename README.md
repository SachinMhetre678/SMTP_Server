# 🚀 Simple SMTP Server

Welcome to the **Simple SMTP Server** project! 🎉 This project allows you to easily handle SMTP connections, log incoming emails, and get started with building email-related applications. Whether you're a beginner or an experienced developer, this server will help you understand and work with the SMTP protocol.

## 🌟 Features

- **📡 Handles SMTP Connections:** Accepts SMTP connections on port 25 with ease.
- **📝 Logs Email Events:** Track important events like connection, sender address, recipient address, and the email content.
- **⚙️ Simple Setup:** Start your server in minutes with just a few commands.
- **🔧 Customizable:** Tailor the server behavior to match your specific needs.

## 🛠️ Getting Started

### Prerequisites

Before diving in, make sure you have Node.js installed. If you haven't installed it yet, you can download it [here](https://nodejs.org/). 🚀

### Installation

1. **Clone the Repository** 📂

    Start by cloning this repository to your local machine:

    ```bash
    git clone https://github.com/SachinMhetre678/smtp-server.git
    cd smtp-server
    ```

2. **Install Dependencies** 📦

    Next, install the required packages:

    ```bash
    npm install smtp-server
    ```

### 🚴‍♂️ Running the Server

To launch the SMTP server, run the following command:

```bash
node server.js
```

You should see:

```bash
Server Running on 25
```

🎉 **Congratulations!** Your SMTP server is now up and running on port 25.

### 🔍 Exploring the Server

The server logs key SMTP events, providing you with insights into how it operates:

- **onConnect:** Logs when a client connects to the server.
- **onMailFrom:** Logs the sender's email address.
- **onRcptTo:** Logs the recipient's email address.
- **onData:** Logs the email content.

**Example Log Output** 📄:

```bash
onConnect 1
onMailFrom sender@example.com 1
onRcptTo recipient@example.com 1
onData From: sender@example.com
To: recipient@example.com
Subject: Test Email

This is a test email.
```

### 🔧 Customizing the Server

Want to add your own touch? ✨ You can easily modify the server's behavior by tweaking the callback functions:

- **onConnect:** Customize what happens when a client connects.
- **onMailFrom:** Decide how to handle the sender's email address.
- **onRcptTo:** Control how recipient addresses are processed.
- **onData:** Manipulate or log the email content as you see fit.

### 📚 Example Use Cases

Here are some ways you can use this server:

- **🛠️ Email Testing:** Use it to test email functionalities in your applications.
- **📊 Email Logging:** Capture and analyze incoming emails for debugging or auditing purposes.

## 🤝 Contributing

Got ideas or improvements? 💡 Contributions are welcome! Feel free to open an issue or submit a pull request. Let's build something awesome together! 💪

## 📖 Learn More

Want to dive deeper into the world of SMTP? Here are some great resources:

- [📚 SMTP Protocol Overview](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol)
- [📖 Node.js SMTP Server Documentation](https://nodemailer.com/extras/smtp-server/)

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---
