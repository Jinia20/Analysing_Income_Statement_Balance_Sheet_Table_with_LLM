# PDF Table Extraction & Summarization

Welcome to the PDF Table Extraction & Summarization project! This application allows you to effortlessly upload PDF documents, extract tables from them, and generate concise summaries using advanced AI models. Built with Streamlit, this tool offers a seamless and interactive user experience.

🚀 **Features**:
- 📤 **Upload PDFs**: Easily upload your PDF documents through a user-friendly interface.
- 👀 **Preview PDFs**: View the content of your PDFs directly within the application.
- 📊 **Extract Tables**: Automatically detect and extract tables from your uploaded PDFs.
- 📝 **Summarize Tables**: Generate insightful summaries of each extracted table using AI-powered summarization.
- 🧹 **Automatic Cleanup**: Ensures temporary files are deleted after processing to maintain security and efficiency.

### 🚀 **Installation**

Follow these steps to set up the project locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/pdf-table-extraction.git
   cd pdf-table-extraction
Create a Virtual Environment (Optional but Recommended):

bash
Copy code
python -m venv venv
Activate the Virtual Environment:

Windows:
bash
Copy code
venv\Scripts\activate
macOS/Linux:
bash
Copy code
source venv/bin/activate
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
🖥️ Usage
Run the Streamlit application using the following command:

bash
Copy code
streamlit run app.py
Once the application starts, follow these steps:

📂 Upload Your PDF: Navigate to the sidebar and use the file uploader to select your PDF document.

🔍 Preview the PDF: After uploading, the application will display a preview of your PDF.

📑 Extract Tables: The app will automatically extract tables from the PDF. View them in expandable sections.

📝 Summarize Tables: Generate and view summaries for each extracted table.

📁 Project Structure
bash
Copy code
pdf-table-extraction/
├── app.py               # Main application file
├── requirements.txt     # Python dependencies
├── utils/               # Utility scripts for table extraction and summarization
│   ├── table_extraction.py  # Script to handle table extraction from PDF
│   └── summarization.py     # Script to summarize extracted table data
├── README.md            # Project overview and instructions
└── assets/              # (Optional) Folder for additional icons or images
    └── icons/           # Folder for storing icon files
🧰 Dependencies
The project relies on the following key libraries:

Streamlit: For building the interactive web application.
Pandas: For data manipulation and analysis.
PyPDF2: For reading and handling PDF files.
Mistralai: For AI-powered summarization (ensure it's correctly installed and configured).
Full List of Dependencies:

Copy code
streamlit
pandas
PyPDF2
mistralai
🌐 Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the Repository
Create a New Branch:
bash
Copy code
git checkout -b feature/YourFeature
Commit Your Changes:
bash
Copy code
git commit -m "Add your message here"
Push to the Branch:
bash
Copy code
git push origin feature/YourFeature
Open a Pull Request
📝 License
This project is licensed under the MIT License.

