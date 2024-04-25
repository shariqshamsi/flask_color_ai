**Flask_color_ai**
Flask_color_ai is a dynamic color palette generator project built using Flask, OpenAI's GPT-3.5-turbo model, CSS, and JavaScript. This project allows users to input simple prompts, such as "generate google brand colors," into a search bar. Based on the prompt, the application generates a corresponding color palette in the background along with its respective color codes. Users can conveniently copy these color codes to their clipboard for use in their projects or designs.

**Features**
- **Dynamic Color Palette Generation:** Enter prompts to generate custom color palettes.
- **Copy Color Codes:** Easily copy generated color codes to your clipboard.
- **Interactive User Interface:** Frontend developed using CSS and JavaScript for a seamless user experience.
- **Secure API Key Storage:** API key required for accessing OpenAI's GPT-3.5-turbo model is stored in a .env file (not included in this repository) for security.

**Technologies Used**
- **Flask:** Backend framework for handling user requests and generating color palettes.
- **OpenAI GPT-3.5-turbo:** AI model used for natural language processing and color palette generation.
- **CSS & JavaScript**: Frontend development for an interactive user interface.
- **Python:** Backend logic for generating color palettes based on user input.

**Additional Information**
- **Virtual Environment (virtualenv):** The project is developed and maintained within a virtual environment to manage dependencies and isolate the project's environment from the system.
- **.env File:** API key for OpenAI's GPT-3.5-turbo model is stored in a .env file, not included in this repository for security.
- **Static Files:** CSS and JavaScript files are stored in the `static` folder as per the Flask project structure.
