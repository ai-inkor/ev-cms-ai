# ev-cms-ai
https://ai-inkor.github.io/ev-cms-ai/
I want to make a small live project for our college event. 
Please help me create everything step by step and also explain what you are doing.

The idea is to build a simple EV-Charger Monitoring System that looks real and works online.

Here is what I want the system to do:

1. There should be one web page that shows:
   - How many chargers are online
   - How much total power is being used
   - A live list of who is currently charging, showing their vehicle number, amount paid, and time

2. There should be another web page where a user can type:
   - Vehicle number
   - Amount they want to pay for charging
   Then click submit. This data should go to an online database automatically.

3. Whatever users submit should appear instantly on the first web page without reloading.

4. For total power used, please assume that every charger consumes 0.01 watt per second while it is active. 
   The dashboard should keep updating this total power value in real time using this simple formula.

I do not know what tools or databases to use.
We can use firebase. 
Give exact steps of how to use Firebase in this project. 
Give a sample json that can be imported to firbase to set up the nodes.
Please select free and easy tools or services that can host both pages and store live data. 
Also explain why you are choosing them.

I want to host the whole project on GitHub so that anyone can open it in a browser and see the live dashboard. 
Please make sure everything can run directly from GitHub without any paid server.

Now please do the following in order:

Step 1: 
Decide which online database we should use and create it. 
Make the required tables or collections to store chargers and user requests. 
Explain in simple language what these tables will do.

Step 2: 
Create all the website files we need. 
You can name them yourself but please explain clearly what each file is for. 
Include the complete code for each file.

Step 3: 
Explain how these files will talk to the online database so that live updates happen automatically and power usage is calculated using the 0.01 watt per second formula.

Step 4: 
Explain how I can upload everything to GitHub and make the pages visible to everyone using GitHub Pages or any similar free method.

Step 5: 
Show me how to test it — I should be able to open one page to enter data and another page to see the dashboard update live with the total power value changing over time.

Step 6: 
Give a short summary at the end explaining how this project is similar to a real EV-Charger monitoring system used in the industry.

Output format:
For every step, show the explanation first and then the code or setup instructions. 
Please make it beginner-friendly and use only free tools.
Do not use separate javascript files use the javascript inside the html only.

To start first give brief of the tools we will use and database setup.
Later we will ask for other files and steps.
