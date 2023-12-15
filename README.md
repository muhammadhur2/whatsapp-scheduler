# Automated Messaging Application

## Overview
This application is designed to automate the process of sending WhatsApp messages, either to individuals or groups, at a specified time. It uses a combination of Python libraries to achieve this functionality.

## Features
- Send personal messages by specifying the recipient's phone number.
- Send group messages by specifying the group ID.
- Schedule messages to be sent at a specific time.

## Dependencies
- `pywhatkit`: For handling the automation of WhatsApp messages.
- `PyAutoGUI`: For simulating keyboard and mouse interactions.
- `keyboard`: For capturing keyboard events.
- `ipywidgets`: For creating interactive elements in Jupyter Notebooks.
- `voila`: For converting Jupyter notebooks into standalone web applications.

## Setup
1. **Conda Environment:**
   - It's recommended to create a new Conda environment for this project.
   - Use the provided `environment.yaml` to set up the environment.
   - Activate the environment using Conda.

2. **Installation:**
   - Install dependencies using both pip and conda commands as specified in the `environment.yaml`.
   - Ensure all packages are installed correctly before proceeding.

3. **Setting Up the Conda Environment:**
   - Open the Anaconda Prompt or your system's terminal.
   - Create a new Conda environment using the provided `environment.yaml` file:
     ```
     conda env create -f environment.yaml
     ```
   - Once the environment is created, activate it:
     ```
     conda activate myenv
     ```
   - This environment will contain all the necessary packages and dependencies to run the application.

## Usage
- Run the Jupyter Notebook to access the user interface.
- Input the details for the message, including recipient, message content, and scheduled time.
- Click the 'Send' button to schedule the message.

## Note
- This application is designed to run in a Jupyter Notebook environment.
- Ensure WhatsApp Web is logged in and accessible on the same machine running the script for successful message delivery.

## License
- This project is licensed under the [MIT License](LICENSE).

## Contributions
- Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## Contact
- For any queries or suggestions, please open an issue in the project's GitHub repository.
