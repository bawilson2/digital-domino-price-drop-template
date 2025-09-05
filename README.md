# Digital Domino Drop: The Price Drop Notifier



## Welcome to the Challenge! 👋

Welcome to the first Digital Domino Drop challenge! This project isn't just about learning to code; it's about learning to **think like an engineer**. You'll connect simple pieces of code together to create a "chain reaction" that accomplishes a fun, useful task.

By the end of this challenge, you will have built a working Python script that monitors a webpage for a price drop and sends you a notification on Discord.

This project is perfect for **curious beginners** who want to build their first practical automation tool.

## The Mission 🎯

Your mission is to build an automated bot that watches an item you want to buy and tells you when it goes on sale. You'll set up a chain of five "dominos" that will trigger one after another:

1.  **Domino #1: The Request.** Fetch the content of a live webpage.
2.  **Domino #2: The Extraction.** Find and extract the product's name and price from the HTML.
3.  **Domino #3: The Memory.** Remember the last price the bot saw.
4.  **Domino #4: The Logic.** Compare the current price to the last one.
5.  **Domino #5: The Alert!** If the price has dropped, send a notification to your phone th rough ntfy.

## How to Get Started (Zero Setup!) 🚀

This project uses GitHub Codespaces, which gives you a powerful, pre-configured development environment right in your browser. No local installation is needed!

1.  **Create Your Copy:** Click the green **"Use this template"** button at the top of this page, then select **"Create a new repository."** This will create your own private copy of the challenge files.

2.  **Launch Your Workbench:** On your new repository page, click the green **`< > Code`** button, select the **"Codespaces"** tab, and click **"Create a codespace on main."**

    

3.  **Start the Challenge:** Wait a minute or two for the Codespace to build. Once it's ready, your environment will be set up with everything you need. Open the Challenge Guide and begin Domino #1!

## What's in this Repository? 📂

* `main.py`: This is the main file where you'll be writing your Python code.
* `price_history.json`: Your script will use this file to remember the last price it saw.
* `.devcontainer/`: This magic folder automatically sets up your Python environment for you in Codespaces.