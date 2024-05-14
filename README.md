 The chatbot is designed to engage in conversational interactions with users, providing responses based on its understanding of the input.

## Installation:

1. Clone the repository: `git clone https://github.com/iamsarthak14/Sunbase-RAG-Assignment.git`
2. Navigate to the project directory: `cd backend/Sunbase-RAG-Assignment`
3. Build the project: `mvn clean install`
4. Start the spring project
5. open the frontend.html file, located in 'frontend' folder in your browser.


## Usage:
Enter Username: Begin by typing your username into the designated field.

Choose File: Click on the "Choose File" button to select the file you want to upload.

Get Text from File: After selecting the file, click on the "Get Text from File" button. The chatbot will display a preview of the text data extracted from the file below.

Submit File: If you're satisfied with the text preview and want to proceed with asking questions based on the file content, click the "Submit File" button.

Manual Data Entry: If you prefer to manually enter data instead of uploading a file, you can do so too. Type your data into the box.

Hit Query Button: Once you've entered your data, click on the "Hit Query" button to submit your query to the chatbot.

View Results: The chatbot will process your query and display the result in the result box below. You can then review the response provided by the chatbot.

## Future Enhancements:
1. Support for multiple file formats.
2. Add a buffer loader in the frontend, signifying when the user request is being processed.
3. Better prompt engineering to make query answers accurate and more aligned with the input data.
