# GenAI_Project1_Multilang_Invoice_extractor


# MultiLanguage Invoice Extractor

This Streamlit application leverages Google's Gemini 1.5 Flash model to analyze multilingual invoices. 
It allows users to upload an invoice image and get meaningful responses based on the input prompt provided.

## Features
- **MultiLanguage Support**: The app can analyze invoices in multiple languages.
- **Invoice Image Upload**: Users can upload invoices in `.jpg`, `.jpeg`, or `.png` formats.
- **Generative AI Integration**: Powered by Google Generative AI (Gemini model), the app generates intelligent responses to questions about the uploaded invoice.
- **Real-time Feedback**: Provides quick insights into the content of the uploaded invoice.

## Technology Stack
- **Streamlit**: Frontend for user interaction.
- **Google Generative AI (Gemini 1.5 Flash)**: AI model for understanding and responding to invoice content.
- **Python**: Core programming language.
- **Pillow**: Image processing library.
- **dotenv**: For managing environment variables.

## Installation

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Create a `.env` file and add your Google Generative AI API key:
   ```bash
   GOOGLE_API=your_google_api_key
   ```

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run main.py
   ```

2. Upload an invoice image and provide an input prompt. The app will use the Gemini model to analyze the image and generate a response.

## Example Prompt
- **Input Prompt**: "Tell me about the invoice"
- **Uploaded Image**: Sample invoice in `.jpg` format

Feel free to adjust the content to suit your style!
