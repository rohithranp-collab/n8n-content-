# n8n-content-
learn from nextwave 
# AI-Powered LinkedIn Post Automation Using n8n and Google Gemini

## 📌 Project Overview

This project automates LinkedIn post creation using **n8n, Google Sheets, and Google Gemini AI**. Whenever data in Google Sheets is updated, the workflow uses Gemini AI to summarize the content and automatically create a LinkedIn post.

The main goal is to save time, reduce manual work, and simplify social media content publishing.

## 🚀 Features

- **Google Sheets Integration:** Triggers the workflow when spreadsheet data changes.
- **AI-Powered Summarization:** Uses Google Gemini AI to summarize the provided content.
- **Automated Workflow:** Connects all steps through n8n.
- **LinkedIn Integration:** Creates LinkedIn posts automatically.
- **Time Saving:** Reduces repetitive content creation and publishing tasks.

## 🛠️ Technologies Used

- n8n – Workflow automation
- Google Sheets – Data storage and trigger
- Google Gemini AI – Content summarization
- LinkedIn API – Post creation

## 🔄 Workflow Architecture

1. **Google Sheets Trigger:** Detects updates in the spreadsheet.
2. **Basic LLM Chain:** Processes the input using a language model.
3. **Google Gemini Chat Model:** Generates AI-powered summaries.
4. **Summarize with Gemini:** Produces the summarized text.
5. **LinkedIn Create a Post:** Publishes the generated content to LinkedIn.

## ⚙️ How It Works

1. Add or update content in Google Sheets.
2. n8n detects the spreadsheet update.
3. The Basic LLM Chain sends the content to Google Gemini.
4. Gemini generates a concise, readable summary.
5. n8n sends the generated content to LinkedIn to create a post.

## 📋 Prerequisites

Before running the project, you need:

- An n8n account or self-hosted n8n instance.
- A Google account with Google Sheets access.
- A Google Gemini API key.
- A LinkedIn account with the required API permissions.
- Configured credentials for the Google Sheets and LinkedIn integrations in n8n.

## 🔧 Setup Instructions

1. Create a Google Sheet and add the content you want to summarize.
2. Open n8n and create a new workflow.
3. Add a Google Sheets Trigger node.
4. Connect a Basic LLM Chain node.
5. Configure the Google Gemini Chat Model.
6. Add the summarization prompt to generate LinkedIn-ready content.
7. Connect a LinkedIn node and select the **Create a Post** operation.
8. Configure the required credentials for each integration.
9. Test the workflow with sample spreadsheet data.
10. Activate the workflow after confirming that the generated posts are correct.

## 💡 Example Use Case

**Input in Google Sheets:**

An article or a long paragraph about artificial intelligence, technology, or industry news.

**AI Processing:**

Google Gemini analyzes the input and creates a concise summary suitable for LinkedIn.

**Output:**

A clear, professional LinkedIn post generated from the spreadsheet content.

## 🎯 Benefits

- Automates repetitive social media tasks.
- Improves content creation efficiency.
- Makes AI-powered summarization easier.
- Connects multiple applications in a single workflow.
- Supports consistent LinkedIn content publishing.

## 🔮 Future Enhancements

- Add AI-generated hashtags.
- Generate multiple post variations.
- Add human approval before publishing.
- Schedule posts for specific dates and times.
- Track post engagement and performance.
- Extend support to other social media platforms.

## 👨‍💻 Author

**Rohith R**

## 📄 License

This project is intended for educational and personal learning purposes. Add an appropriate open-source license if you plan to distribute the project publicly.
