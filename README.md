NexusAI – Telegram AI Assistant 🤖

About the Project

NexusAI is my AI-based Telegram Assistant project. I developed this project using n8n automation and Google Gemini AI.

The main purpose of this project is to make studying easier for students. Users can ask questions on Telegram and get answers from AI. It can also understand Marathi and English messages.

Users can upload PDF files and ask questions related to the uploaded documents. The AI assistant reads the PDF content and provides answers.

Features

- Answers questions using Google Gemini AI.
- Supports Marathi and English languages.
- Helps students understand Python, Java, programming, and other subjects.
- Accepts PDF documents through Telegram.
- Reads and explains uploaded PDF files.
- Remembers previous conversations using Simple Memory.
- Sends AI-generated responses through Gmail.
- Automates the complete process using n8n.

Technologies Used

- n8n: Used to create and manage the workflow.
- Telegram Bot: Used to communicate with users.
- Google Gemini AI: Used to generate answers.
- Gmail: Used to send email responses.
- AI Agent: Used to process user questions.
- Simple Memory: Used to maintain conversation context.
- PDF Extractor: Used to extract text from PDF files.

How My Project Works

1. Text Message Processing

1. The user sends a message to the Telegram bot.
2. Telegram Trigger receives the message.
3. Edit Fields extracts the required information.
4. Switch checks the message type.
5. AI Agent processes the question.
6. Google Gemini generates the answer.
7. Simple Memory maintains the conversation context.
8. The answer is sent back to the user on Telegram.
9. Gmail also sends the generated response.

2. PDF Processing

1. The user uploads a PDF file on Telegram.
2. The bot receives the document.
3. Get a File downloads the PDF.
4. Extract from File extracts the text.
5. AI Agent reads and understands the extracted content.
6. Google Gemini generates an answer.
7. The answer is sent to Telegram.
8. Gmail sends the response through email.

Example

User: Explain Python in simple words.

NexusAI: Python is a simple and popular programming language used for web development, automation, AI, and data science.

User: Uploads a PDF and asks a question.

NexusAI: Reads the PDF content and provides an answer based on the document.

Future Scope

In the future, I would like to add:

- Voice message support.
- Image understanding.
- RAG-based knowledge base.
- Quiz and MCQ generation.
- Personalized study assistance.

What I Learned

While developing this project, I learned:

- How to create workflows in n8n.
- How to connect Telegram Bot with n8n.
- How to integrate Google Gemini AI.
- How to use AI Agent and Simple Memory.
- How to extract information from PDF files.
- How to automate email responses using Gmail.

Developed By

Vaishnavi Chavan

Computer Science and Engineering Student

Project: NexusAI – Telegram AI Assistant

⭐ Thank you for visiting my project repository!
