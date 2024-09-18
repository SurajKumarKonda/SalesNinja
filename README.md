# SalesNinja

SalesNinja transforms sales management through AI, automating tasks, providing real-time insights, optimizing forecasts, and enabling personalized interactions. It empowers sales teams to increase productivity, improve accuracy, and drive growth by leveraging data-driven strategies and freeing up time for high-value activities like building relationships and closing deals.

# ChatBot

## Installation & Setup

[Install Python] https://www.dataquest.io/blog/installing-python-on-mac/

[Install pip] https://phoenixnap.com/kb/install-pip-mac

If you have Python & pip installed then check their version in the terminal or command line tools

```
python3 --version
```

```
pip --version
```

## Installing Flask

In your terminal run the requirements.txt file using this pip

```
pip install -r requirements.txt
```


## Running ChatBot Application in Terminal

```
cd into your directory
```

```
python app.py
```



## What have I done?

I'll walk you through the process of creating a chatbot that engages in conversations with users through natural language processing.

We will be leveraging Microsoft DialoGPT, a pre-trained language model known for generating human-like responses to prompts. To build our web application, we will integrate DialoGPT with Flask, a popular Python web framework, allowing for seamless communication with users via a chat interface.

For the front-end, we will use HTML, CSS, and JavaScript to design an attractive and interactive chat interface. Additionally, we will incorporate jQuery to manage the HTTP requests sent to our backend server.

This tutorial will provide detailed, step-by-step guidance on setting up your development environment, installing necessary dependencies, and creating the required files and code for the application. I will also cover how to train and fine-tune the DialoGPT model to enhance response accuracy.

By the end of this tutorial, you will have a fully operational chatbot capable of conversing with users, and you will have gained valuable experience with Microsoft DialoGPT, Flask, and web development technologies such as HTML, CSS, and JavaScript.

# ChatBot Link
The Chatbot is constructed using the Microsoft/DialoGPT-medium model.

```
https://huggingface.co/microsoft/DialoGPT-medium
```

# User-HTML

```
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';
```

# Bot-HTML

```
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```
