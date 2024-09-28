OCR Web Application

Project Overview
This project is a web-based prototype that performs Optical Character Recognition (OCR) on uploaded images containing text in both Hindi and English. The application allows users to upload a single image, extracts the text using an OCR model, and includes a basic keyword search feature. The web application is developed using Streamlit and is deployed on a platform accessible via a public URL.

Features:
OCR for Hindi and English: Extract text from uploaded images.
Keyword Search: Search for specific keywords within the extracted text.
User-Friendly Interface: Upload an image, view the extracted text, and perform keyword searches on a single page.

Setup Instructions
1. Environment Setup
Prerequisites:
Python 3.8 or above
Pip package manager
Install required dependencies:
To set up the Python environment, run the following command to install necessary dependencies:

pip install torch transformers streamlit Pillow
The project is based on OCR models, and the following models were explored:
General OCR Theory (GOT)

2. Running the Application Locally
Steps to Run the App:
Clone the repository: If you haven’t already, clone the repository or download the project files.

git clone https://github.com/your-username/ocr-web-app.git
cd ocr-web-app
Install Dependencies: Ensure you have installed all the dependencies as mentioned above.
You can use the following command:

pip install -r requirements.txt

Running the Application: To launch the application, run the following command:

streamlit run streamlit_app.py

Access the Application: Once the application starts, you will see a local URL in your terminal.
Open the URL in your browser to interact with the application.

3. OCR Model Implementation
OCR Model:

The OCR functionality is powered by either the ColPali (Byaldi Library + Huggingface transformers for Qwen2-VL) model or the General OCR Theory (GOT) model. The implementation is included in streamlit_app.py.
Image Upload and Text Extraction:

Users can upload images in common formats such as JPEG or PNG.
The OCR model processes the uploaded image and extracts the text, which is displayed on the same page in a structured format (plain text).
Keyword Search:

After the text extraction, users can enter keywords to search within the extracted text.
The matching sections of the text are highlighted in the output.

4. Deployment
Deploying on Streamlit Sharing
To deploy the application on Streamlit Sharing, follow these steps:

Upload the Project to GitHub: Ensure all project files, including app.py and requirements.txt, are pushed to a GitHub repository.

Create a Streamlit Sharing Account: Sign up for Streamlit Sharing at Streamlit Cloud.

Deploy the App: Connect your GitHub repository to Streamlit Sharing.

After linking the repository, Streamlit will automatically deploy the app.
You will receive a public URL for accessing the application.

5. Public URL
Once deployed on Streamlit Sharing, you can access the application via the live URL. Share this URL with others for demonstration and testing purposes.
https://projectocr-gzqjquz9g8fitjd5xxz92a.streamlit.app/



For queries or contributions, feel free to open an issue or contact us at sneha15sep04@gmail.com.
