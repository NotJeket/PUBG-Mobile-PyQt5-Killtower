**Kill** **Tracker**

Kill Tracker is a PyQt5 application that displays the live status of players in a PUBG match. The application retrieves data from an API and displays it in a table format, where the team names are listed in the left column and the players' status (Alive/Dead) are listed in the right column.

**Updates and Features from the Tkinter Killtower**

- A PyQt5 graphical user interface (GUI) that displays a table with team names and their players.
- The GUI updates the data every second using a timer.
- The data is obtained from an HTTP GET request to an API endpoint at "<http://127.0.0.1:5000/data1>".
- The JSON data returned by the API is parsed to extract the team names and the number of live players for each team.
- The team names and the number of live players are displayed in the GUI table.
- The background color of the player status cells in the GUI table is set based on the number of live players. Green indicates that all players are alive, yellow indicates that some players are dead, and red indicates that all players are dead.

**Screenshot**

![Aspose Words 1263b14c-3107-48d7-bf53-dbf05a3ad8e7 001](https://user-images.githubusercontent.com/37781149/233176854-bc96282f-abb7-4eca-b040-af5b0bf3747e.png)

**Diagram**

![Aspose Words 1263b14c-3107-48d7-bf53-dbf05a3ad8e7 002](https://user-images.githubusercontent.com/37781149/233179251-2d81ca9d-e78b-47c8-a4d6-09f057b8b4be.png)

**Installation**

1. Clone the repository or download the code.
1. Install the necessary libraries by running the following command in your terminal:

pip install PyQt5 requests 

**Contributing**

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

**Usage**

To use this program, you will need to have Python 3 and the PyQt5 and requests libraries installed. Once those are installed, you can run the program by executing the kill\_tracker.py file with Python.

When the program is running, it will display a window with a table showing the status of each team in the game. The table will update every second with the latest data from the API.

**Dependencies**

This program has the following dependencies:

- Python 3
- PyQt5
- requests

**Configuration**

To configure the program, you will need to modify the API URL in the update\_data method of the KillTracker class to match the URL of the API that you want to use.

**Troubleshooting**

If you encounter any issues with the program, please make sure that you have Python 3 and the required libraries installed. If you are still having issues, please check the console output for any error messages and consult the documentation for the libraries being used.

**License**

This program is licensed under the MIT License. See the LICENSE file for more information.

