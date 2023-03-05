# **Mort - The Movie Recommender Chatbot: Pick Your Flix the New Way**

Welcome to Mort, the one-stop bot that delivers the movie you're looking for. Mort is a chatbot that recommends the best movies based on your preferences. With Mort, you no longer need to go through irrelevant search results to find a good movie to watch.

# **Features**

Mort offers several features that make it stand out from other movie recommendation websites and bots:

- Filtered recommendations based on your preferences
- Top results only; scans through all the relevant results on the web
- The bot does the research for you
- Uses GPT from OpenAI to provide a human-like feel

# **Dependencies**

Mort relies on the following Python packages:

- streamlit
- pandas
- numpy
- requests
- json
- openai

You can install them using the pip package manager.

# **How it works?**

The code is a Python script that uses the OpenAI API to generate movie recommendations based on user input. It uses the streamlit library to create a simple chat interface that allows the user to input text and receive recommendations in response.

The ```get_text()``` function takes care of handling user input. It creates a text input field using streamlit, waits for the user to input some text, and then stores the user's input in the past session state variable. It also displays the user's input in the chat interface using the ```message()``` function from the streamlit_chat library.

The ```generate_text()``` function is responsible for generating movie recommendations based on a given prompt. It uses the OpenAI API to generate text based on the prompt and returns the top recommendation as a string.

The ```handle_recommendation()``` function takes care of displaying the recommendations to the user. It takes the generated text as input, parses it as a JSON array, and then displays the title, synopsis, image, trailer URL, and genre for each recommended movie using streamlit's built-in functions.

The ```get_recommendation()``` function is responsible for generating recommendations based on the user's input. It retrieves the user's most recent input from the past session state variable, generates recommendations based on that input using ```generate_text()```, and then displays the recommendations using ```handle_recommendation()```.

The ```add_buttons()``` function is currently not being used, but it is intended to add buttons to the chat interface that allow the user to request more recommendations based on certain prompts.

The ```init()``` function sets up the chat interface and initializes the session state variables. It displays a welcome message using ```message()``` and then waits for the user to input some text using ```get_text()```. Once the user has input some text, it generates recommendations based on that input using ```get_recommendation()```, displays the recommendations using ```handle_recommendation()```, and then waits for the user to input more text. The ```init()``` function also sets up the buttons using ```add_buttons()```, although these buttons are currently not being used.

# **Getting Started**

Here are the steps to get Mort up and running on your local machine:

- Install PyCharm, an integrated development environment for Python.
- Install Anaconda, a distribution of the Python and R programming languages for scientific computing.
- Create a new environment called "Chatbot" (or any other name you prefer) in Anaconda.
- Open the .py file using PyCharm.
- Install all the imported dependencies listed on the first few lines of the code using pip install method.
- Make sure you are in the file directory for the Chatbot environment and use the tab key to find the file/folder. Then only would the bot run and automatically open in a new tab on your default browser.
- If using Anaconda as the Python interpreter does not work, you can install Python and use it as an interpreter.

**Note**:
The code in the repository does not mention the OPENAI API KEY. Therefore, you need to use your own OpenAI API Key to run the code.

# **How to Run the Bot**

Once you've set up the environment and installed the required packages, you can run the bot by following these steps:

- Open PyCharm and open the project containing the bot code.
- Make sure you are in the environment you created earlier (i.e., Chatbot).
- Open a terminal in PyCharm and navigate to the directory where you've saved the bot code.
- Run the command:
```
streamlit run FILENAME.py
```
(replace FILENAME with the name of the file containing the bot code).
- Wait for a few seconds until the bot opens in a new tab on your default browser.

# **Team Members**

Mort was developed by a team of four members:

- Danush Khanna (myself) danush.s.khanna@gmail.com
- Navansh Khandelwal khandelwalnavansh1@gmail.com
- Sanyam Jain sanyam0605@gmail.com
- Srivaishnavi Yaddanapudi 2003ysv@gmail.com

# **Contact Us**

If you have any questions or comments, please feel free to contact us at our GitHub repository or email.

# **Contributions**

If you're interested in contributing to Mort, please feel free to fork this repository and submit a pull request. We welcome any feedback, suggestions, or bug reports.

# **License**

Mort is licensed under the <ins>MIT License</ins>.

# **Conclusion**

Mort is the perfect solution for movie lovers who struggle to find the right movie to watch. With its filtered recommendations and top results, you no longer have to spend hours searching for a good movie to watch. Follow the instructions above to get started with Mort today!

Whether you're looking for a new blockbuster or a hidden gem, Mort has got you covered. With Mort, you can now pick your flix the new way.

# **Screenshots**

<img width="1439" alt="Screenshot 2023-03-04 at 2 08 02 PM" src="https://user-images.githubusercontent.com/113158564/222944104-71848908-e6f7-40fc-9559-97fc11ebd3ac.png">
<img width="1437" alt="Screenshot 2023-03-04 at 2 08 29 PM" src="https://user-images.githubusercontent.com/113158564/222944112-cf3579f3-47c3-4629-942c-f0fcebe3dd7f.png">
<img width="829" alt="Screenshot 2023-03-04 at 7 11 25 AM" src="https://user-images.githubusercontent.com/113158564/222944115-4456d08d-d950-4f7e-9db4-2ab99964ff5b.png">
![potc 2 pic](https://user-images.githubusercontent.com/113158564/222974191-f3b9de0a-eadd-4c45-bda5-d0b646147ac7.png)
<img width="851" alt="Screenshot 2023-03-04 at 7 14 51 AM" src="https://user-images.githubusercontent.com/113158564/222944117-132a1426-4e08-41b3-90aa-a387dd3e9d6f.png">
![blade 2 pic](https://user-images.githubusercontent.com/113158564/222974196-7478158e-3913-4476-ace8-bfbf4cf3f6d5.png)





