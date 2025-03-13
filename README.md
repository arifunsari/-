# Azure Blob OCR & Face Detection

##  Unlock the Power of AI with Azure Blob OCR & Face Detection! 🧑‍💻📸

### Overview
This project is a Streamlit-powered application that integrates multiple Azure AI services to deliver an exceptional experience in:

1️⃣ **OCR (Optical Character Recognition)**: Extracting text from images.
2️⃣ **Face Detection**: Identifying and cropping faces in images.
3️⃣ **Azure Blob Storage Management**: Seamlessly uploading and managing images in Azure Blob Storage.

This app showcases the power of **Machine Learning, Azure Cognitive Services, and Python**, enabling us to build cutting-edge, interactive solutions! 🌐✨

---

## 💡 Key Features

- **Text Extraction (OCR)**: Using Azure's Computer Vision API, accurately extract text from uploaded images.
- **Face Detection**: Leveraging Azure's Face API to detect faces and crop them dynamically.
- **Azure Blob Storage**: Managing and storing images securely with Azure's cloud storage.
- **Interactive Interface**: Built with Streamlit, offering a clean and user-friendly experience.
- **Custom Backgrounds**: Adding a professional touch with CSS and base64-encoded images.

---

## 💻 Technical Concepts

- **Streamlit**: A Python library to create web applications effortlessly.
- **Azure Computer Vision API**: OCR capabilities, processing image streams to extract text.
- **Azure Face API**: Detect faces in images and provide precise bounding boxes.
- **Azure Blob Storage**: Secure and scalable cloud storage for image management.
- **Python PIL Library**: For image processing, including cropping detected face regions.
- **Azure SDKs**: To interact with various Azure services programmatically.
- **Dynamic Polling**: Ensuring smooth async operations while waiting for Azure's OCR results.

---

## 🌟 Challenges Solved

- **Simplified text extraction** for document automation tasks.
- **Enhanced face detection** for security and image processing applications.
- **Streamlined storage** with cloud-native integration via Azure Blob Storage.

---

## 🔧 Installation & Setup

### Prerequisites:
- Python 3.8+
- Azure Subscription
- Azure Cognitive Services API Keys
- Streamlit installed (`pip install streamlit`)

### Steps to Run the Project:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/azure-blob-ocr-face-detection.git
   ```

2. Navigate to the project directory:
   ```sh
   cd azure-blob-ocr-face-detection
   ```

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Set up environment variables for Azure API keys:
   ```sh
   export AZURE_OCR_KEY="your_ocr_key"
   export AZURE_FACE_KEY="your_face_key"
   export AZURE_STORAGE_CONNECTION_STRING="your_storage_connection_string"
   ```

5. Run the application:
   ```sh
   streamlit run app.py
   ```

---

## 📂 Project Structure
```
├── app.py  # Main Streamlit application
├── requirements.txt  # List of dependencies
├── utils.py  # Helper functions for Azure API calls
├── README.md  # Project documentation
├── config.py  # Configuration settings
├── assets/  # Folder containing images & icons
└── data/  # Sample image data
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact
For any queries, reach out at [your-email@example.com](mailto:arifcse2024@gmail.com).

