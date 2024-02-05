## Flask Application Design for a GenAI Based Learning Assistant

### HTML Files

**1. index.html**
- **Purpose:**  Serves as the home page for the AI assistant.
- **Content:** Includes a text input field, a submit button, and an output area for displaying responses.

**2. style.css**
- **Purpose:**  Defines CSS styles for the HTML elements.
- **Content:** Includes rules for formatting the text fields, buttons, and the output area.

### Routes

**1. / (GET)**
- **Purpose:**  Handles GET requests to the home page.
- **Functionality:** Displays the index.html template.

**2. /query (POST)**
- **Purpose:**  Handles POST requests from the text input field.
- **Functionality:** Accepts a question in the form of a text string from the input field and passes it to the AI model for processing. The AI model generates a response, which is then formatted and displayed in the output area of the home page.

**3. /docs (GET)**
- **Purpose:**  Handles GET requests to the documentation page.
- **Functionality:** Displays a page that provides a detailed description of how to use the learning assistant, its capabilities, and the expected format of user queries.