AI Prompt Template Generator
1. Overview
The AI Prompt Template Generator is a user-friendly, browser-based application designed to help users create, manage, and refine detailed prompt templates for use with various AI models. It provides a structured form to ensure all critical aspects of an application or project are considered, leading to more effective and comprehensive AI-generated outputs (like code, technical plans, or documentation).

This tool operates entirely client-side, storing all prompt templates directly in your browser's localStorage. This means your data stays private, and no internet connection is required after the initial page load.

2. Key Features
Structured Prompt Creation: A comprehensive form guides users through defining application type, objectives, technical stack, key features, UI/UX style, and more.

Dynamic Prompt Generation: Instantly generates a well-formatted, multi-section text prompt based on the filled form.

Local Storage: Saves all your prompt templates securely in your browser's localStorage for persistence across sessions.

Load & Edit Saved Prompts: Easily load previously saved templates back into the form for review, modification, or reuse.

Optional Prompt Conclusion: A checkbox allows users to decide whether to include a standard concluding instruction phrase at the end of the generated prompt.

Copy to Clipboard: Quickly copy the generated prompt text with a single click.

Clear Form: Reset the form to its default state.

Responsive Design: The UI adapts to different screen sizes, providing a good experience on desktops, tablets, and mobile devices.

User-Friendly Interface: Inspired by modern design principles, featuring a clean layout, Roboto font, and Material Icons for intuitive interaction.

3. How to Use / Getting Started
As this is a single HTML file application, getting started is very simple:

Download the HTML File: Obtain the ai_prompt_generator.html (or similarly named) file.

Open in Browser: Open the HTML file directly in any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

Define Your Application:

Fill out the fields in the "Define Your Application" form on the left. Required fields are marked with a red asterisk (*).

Use the "Key Features" and "Specific Instructions" textareas to list items, one per line.

Decide if you want the standard concluding instruction by checking/unchecking the "Include standard concluding instruction" checkbox.

Generate & Save:

Click the "Generate & Save Prompt" button (with the play_arrow icon).

The generated prompt will appear in the "Generated Prompt" section on the right.

The prompt configuration will also be saved to your browser's localStorage.

Manage Prompts:

View Generated Prompt: Review the text in the "Generated Prompt" area.

Copy Prompt: Click the "Copy to Clipboard" button (with the content_copy icon) to copy the text.

View Saved Prompts: Previously saved prompts will appear in the "Saved Prompts" list.

Load a Saved Prompt: Click on a saved prompt item in the list, or click its file_open icon, to load its details back into the form and view its generated prompt. The loaded prompt card will be highlighted.

Delete a Saved Prompt: Click the delete icon on a saved prompt card. You'll be asked for confirmation.

Clear Form: Click the "Clear Form" button (with the clear_all icon) to reset all input fields.

4. UI Overview (Roboto UI Style)
The application features a clean and modern interface inspired by the provided HTML/CSS snippet:

Layout: A two-column layout on larger screens (form on the left, output/saved prompts on the right) and a single-column layout on smaller screens.

Font: Uses the "Roboto" font family for excellent readability.

Styling:

Header: A prominent header with the application title and a brief description, set against a white background with a subtle shadow.

Cards: Main content areas (form, generated prompt, saved prompts) are presented as white cards with rounded corners (12px), padding (24px), and a soft box shadow.

Form Inputs: Fields have rounded corners (8px), consistent padding, and a clear blue focus state. Labels are distinct and easy to read.

Buttons:

Primary actions (e.g., "Generate & Save Prompt") use a blue background with white text.

Secondary actions (e.g., "Clear Form", "Copy to Clipboard") use a light gray background with darker text.

Buttons incorporate Material Icons for enhanced visual cues.

Generated Prompt Display: Shown in a styled textarea with a dashed border and a light background, clearly differentiating it as an output area.

Saved Prompt Items: Displayed as individual light gray items with clear text and icon buttons for "Load" and "Delete" actions.

Footer: A simple footer with copyright information.

5. Technologies Used
HTML5: For the basic structure of the application.

Tailwind CSS (v3 via CDN): For utility-first CSS styling.

Vanilla JavaScript (ES6+): For all application logic, DOM manipulation, and interaction.

Roboto Font (via Google Fonts): For typography.

Material Icons (via Google Fonts): For UI icons.

6. Data Storage
All prompt templates and their configurations are stored locally in your web browser's localStorage.

Privacy: Your data is not sent to any server and remains private to your browser.

Persistence: Data persists across browser sessions on the same computer and browser profile.

Limitations:

localStorage has a size limit (typically 5-10MB per domain).

Data is not automatically synced across different browsers or devices.

Clearing your browser's cache/site data for this page may delete your saved prompts. Consider manually backing up important prompts if needed (e.g., by copying the generated text to a separate file).

7. Future Enhancements (Potential Ideas)
Import/Export: Allow users to export their saved prompts to a JSON file and import them, facilitating backups and sharing.

Advanced Editing: Provide an option to directly edit the generated prompt text before saving or copying.

Tagging/Categorization: For better organization of saved prompts.

More Granular Template Options: Add more detailed fields or sections for even more specific prompt engineering.

Direct AI API Integration: (Would require backend/API key management) Option to send the generated prompt directly to an AI service.

This README provides a comprehensive guide to the AI Prompt Template Generator. Enjoy creating your prompts!
