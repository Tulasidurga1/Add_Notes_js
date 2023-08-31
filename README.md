# Add_Notes_js
# Hosted_Link:-https://tulasidurga1.github.io/Add_Notes_js/
# explanation:-
# HTML Structure:-

# The HTML file starts with the usual <!DOCTYPE html> declaration and contains an HTML structure with a <head> and <body> section.
Inside the <head>, necessary meta tags are included for character set and viewport settings. Bootstrap CSS and a custom CSS file ("style.css") are linked for styling.
The title of the web page is set as "NotesWall."
Body Structure:

 # The main content of the web page is structured within the <body> element.
 # The content is divided into two main sections: the header and the notes list.
Header Section:

# The header section has a <div> element with the class "header" and "content." This is where the note input area is placed.
Inside the "content" <div>, there is a "note-input" <div> containing a <textarea> for entering notes and an action section with an input for color selection and a "Add note" button.
JavaScript Implementation:
# JavaScript code is placed at the bottom of the <body> to enhance the interactivity of the application.
It starts by selecting the necessary DOM elements using document.querySelector() and setting up event listeners.
Event Listeners:

# An event listener is added to the "Add note" button (#add-btn) to call the addNewNote function when the button is clicked.
An event listener is also added to the entire document to listen for the Enter key press (keyCode 13) and trigger the addNewNote function.
addNewNote Function:

# This function is responsible for adding a new note to the allNotes array if the input field is not empty.
The new note object includes the note text and the selected color.
After adding the note to the array, the input field is cleared, and the displayNotes function is called.
displayNotes Function:

# This function is responsible for displaying the notes on the webpage.
It clears the content of the "notes-list" element and then iterates through each note in the allNotes array.
For each note, an HTML structure is dynamically created with the note content and color.
The HTML structure is then inserted at the beginning of the "notes-list" element.
An event listener is added to the delete button of each note to call the deleteNote function.
deleteNote Function:

# This function is triggered when the delete button for a note is clicked.
It identifies the parent element of the delete button and removes it from the DOM.
The corresponding note is also removed from the allNotes array.
CSS Styling:

# The CSS styles in the <style> tag define the appearance of various elements on the page.
Styles are provided for the header, note input area, notes list, individual notes, colors, and more.
Footer Section:

# The footer includes a link to the author's LinkedIn profile and is styled with a simple design.
The end result of this code is a web application where users can input notes, choose colors, and add them to a "NotesWall." The notes are displayed with the selected colors, and users can delete notes individually. The overall design is enhanced with Bootstrap and custom CSS styles.




