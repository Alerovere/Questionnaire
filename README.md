# Questionnaire

This is a Python script that generates a multi-choice questionnaire with random questions from a spreadsheet. This project was created to help teachers quickly generate exams for their classes, without having to manually select questions and shuffle the answer choices.

## How it works

The input for the script is a spreadsheet that contains questions organized by lectures, with one correct answer and three incorrect answers. A sample spreadsheet is provided to help you get started. 

The script reads the spreadsheet and prompts the user to enter the number of questions they want to include for each lecture. It then randomly selects the specified number of questions for each lecture, shuffles the answer choices for each question, and saves the results in a Microsoft Word document. Additionally, a text file containing the correct answers is generated for the teacher's reference.

To generate parts of this script, we used ChatGPT, a large language model trained by OpenAI, based on the GPT-3.5 architecture. ChatGPT helped us refine our wording and improve the clarity of the instructions.

## Technical Details

To create the script, we used the pandas library to read the data from the spreadsheet, and the python-docx library to generate the Word document. The code was written in Python 3 and can be run from a Jupyter Notebook.

## How to use it

To use the script, you will need to have Python 3 installed on your computer. You can download it from the official Python website: https://www.python.org/downloads/

Once you have Python installed, you can download the script from the project's GitHub repository: [insert link to your repository]. The repository also includes a sample spreadsheet that you can use to test the script.

You will need to add the name of the spreadsheet and the number of questions you want to include for each lecture. It will then generate a Word document with the questionnaire and a text file with the correct answers.

## Future improvements

It would be great to add more customization options to the script, such as the ability to change the font size and style, and to include images and diagrams in the questions. Also, adding support for other formats, such as PDF and HTML, and to make the script more user-friendly by adding a graphical user interface (GUI).
