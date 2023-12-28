Flatacuties - An Animal Character Voting Application

OVERVIEW
This application allows users to view a list of animal characters, vote for their favorites, reset the votes, and add new animals to the list. It uses a simple local server to serve character data from a db.json file and displays this data in a web interface.

KEY FEATURES
1. View Animal Characters: Display a list of animal characters fetched from a local server.
2. Vote for Animals: Each animal character can receive votes from users.
3. Reset Votes: The votes for a specific animal can be reset to 0.
4. Add New Animals: Users can add new animal characters through a form.

SETUP
Prerequisites
1. Ensure you have Node.js installed on your machine. 
2. Install JSON Server globally. Run npm install -g json-server.

Starting the Server
Create a db.json file with the initial animal character data. 
Start JSON Server by running: json-server --watch db.json. This will serve your db.json file as a REST API on http://localhost:3000.

USING THE APPLICATION
1. Viewing and Voting for Animals
- Open the provided HTML file in a web browser.The application will display a list of animal characters fetched from the local server.

2. Click on any animal's name to view its details, including an image and the current number of votes.

3. Click the "Vote" button to increase the vote count for that animal.

4. Click the "Reset Votes" button to reset the votes for that animal back to 0.

5. Adding New Animals
Use the form at the bottom of the page to add new animal characters.Enter the name and image URL of the new animal and click "Add Animal".
The new animal will be added to the list and can be voted on like the others.

LIMITATIONS
The added animals and vote changes are not persistent. If the page is reloaded, these changes will be lost, as they are not saved back to the db.json file.
The application is intended for demonstration purposes and runs on a local server.

CONTRIBUTING
No contributions are required since this is for practice and demonstration purposes only. 

This README provides a general overview and instructions for setting up and using the animal character voting  application. 


