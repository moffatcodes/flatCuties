Flatacuties
Flatacuties is a web application that allows users to view and vote for their favorite characters from a collection. This application is built using HTML, CSS, and JavaScript, and communicates with a backend API implemented using Express.

Getting Started
To get started with Flatacuties, follow the steps below:

Clone the repository to your local machine using git clone.
Open the index.html file in your preferred web browser.
Interact with the application by viewing the characters, voting for them, and resetting the votes.
Features
Flatacuties includes the following features:

Displaying a list of characters fetched from the backend API.
Viewing detailed information of a selected character, including their image and vote count.

Voting for a character and updating the vote count dynamically.
Resetting the vote count for all characters with a single click.

Code Structure
The code for Flatacuties is organized into different functions and event listeners:

fetchGifs(): Fetches character data from the backend API and displays the characters on the webpage.

displayCharacters(characterArr): Generates a <span> element for each character and appends it to the character bar.

generateSpan(characterObj): Generates a <span> element for a character, sets its properties, and appends it to the character bar.

clickSpanForDetails(characterSpan): Adds a click event listener to a character span to display its detailed information.

firstSpan(characterSpan): Automatically selects and displays the details of the first character when the page loads.

mainCharacterDisplay(character): Displays the detailed information of a selected character, including their image and vote count.

createCharacter(): Adds a submit event listener to the character form to create a new character and update the display.

submitVotesForm(): Adds a submit event listener to the votes form to update the vote count of a character and reset the form.

resetVotes(): Adds a click event listener to the reset button to reset the vote count of all characters.

DOMContentLoaded event: Listens for the DOMContentLoaded event and invokes the necessary functions to fetch data, set up event listeners, and initialize the application.


Technologies Used
Flatacuties is built using the following technologies:


JavaScript: For implementing the logic and interactivity of the application.

If you'd like to contribute to Flatacuties, feel free to submit a pull request with your changes. Please follow the standard coding practices and conventions used in the existing code.

License
Flatacuties is open-source software licensed under the MIT License. Feel free to use, modify, and distribute the code for personal or commercial purposes.