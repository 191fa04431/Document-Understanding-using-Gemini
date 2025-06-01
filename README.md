# Document-Understanding-using-Gemini

This project demonstrates the use of **Gemini AI** for intelligent document understanding. Gemini models support **native PDF vision**, enabling them to read, interpret, and extract data from complex documents — including text, images, charts, tables, and diagrams.

## 🚀 Features

- 📄 Accepts PDF input including long documents (up to 1000 pages)
- 🔍 Analyzes diagrams, charts, and tables inside documents
- 📦 Extracts information into structured output formats (e.g., JSON)
- ❓ Answers questions based on both textual and visual content
- 📝 Summarizes documents
- 🗣️ Transcribes documents (including handwritten or scanned PDFs)

## 🛠️ Technologies Used

- **Python**
- **Google Generative AI SDK** (`google.generativeai`)
- **Gemini 1.5 Flash Model**
- **Pillow** for image processing
- **Google Colab** (or any Jupyter environment)

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Document_Understanding_using_gemini.ipynb` | Main notebook demonstrating Gemini AI for document understanding |

## 📸 Sample Use Cases

1. **Automated Document Review**
2. **Knowledge Extraction from Research Papers**
3. **Customer Support Document Analysis**
4. **Table & Figure Parsing in Financial Documents**

## 🔧 Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/document-understanding-gemini.git
   cd document-understanding-gemini

2. Install dependencies:
    pip install google-generativeai pillow

3. Set your Gemini API Key:
  import google.generativeai as genai
  genai.configure(api_key="your_api_key_here")

4. Run the notebook:
  - Open Document_Understanding_using_gemini.ipynb in Jupyter or Colab and follow the cells step-by-step.

## Example Output
✅ Extracted text from complex document layouts

✅ Visual Q&A on charts/figures inside the PDF

✅ Summarized long documents into concise highlights

## 🤖 Model Used
- Gemini 1.5 Flash via generativeai.GenerativeModel(model_name="gemini-1.5-flash-latest")

### Give this repo a ⭐ if it helped you!
