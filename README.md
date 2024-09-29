# FLUXA AI

Fluxa is a cutting-edge, proprietary application designed for efficient text summarization and PDF processing. It employs state-of-the-art deep learning models, particularly transformers, to provide high-quality, real-time summaries. The application includes Optical Character Recognition (OCR) for PDF documents that contain images, allowing for comprehensive text extraction.

<img src="assets/refrigerator.png" alt="Fluxa Logo" width="400"/>

## Features

- **Text Summarization**: Utilizes a fine-tuned BART (Bidirectional and Auto-Regressive Transformer) model to condense long pieces of text into coherent and concise summaries.
- **PDF Summarization**: Capable of extracting text from PDF files and applying OCR to images within the PDFs to recognize embedded text.
- **Real-Time Processing**: High-speed processing ensures that even large documents are summarized quickly and accurately.

## How It Works

1. **Text Summarization**: The user inputs text that the model processes, leveraging advanced transformer-based architectures like BART to generate a summarized version. The BART model operates as a sequence-to-sequence framework, which is highly effective for tasks involving text generation, translation, and summarization.
   
2. **PDF Upload and OCR**: For PDF files, the application uses PyMuPDF to extract text directly from PDF documents. For pages with images, the Tesseract OCR engine is utilized to perform text recognition. This combination ensures that both digital text and scanned text can be processed and summarized effectively.

3. **Model Architecture**: The core summarization engine uses a pre-trained BART model fine-tuned for summarization tasks. BART operates using an encoder-decoder mechanism where the input sequence is first encoded into a latent space, and the decoder generates the summarized output. Techniques such as beam search and length penalties are employed to ensure high-quality outputs, even for diverse and complex texts.

## Advanced Techniques

- **Transformers**: At the heart of the system is the transformer architecture, which enables the model to capture long-range dependencies in the input text. This is critical for generating contextually aware and semantically accurate summaries.
  
- **OCR Integration**: The app integrates OCR via the Tesseract engine, which is particularly useful for processing scanned documents or PDFs containing images with embedded text. The extracted text is then passed through the BART model for summarization.

- **GPU Acceleration**: For improved performance, the model supports GPU acceleration, which significantly speeds up both the text generation and OCR processes.

## Access

The application is available online at [Fluxa](https://www.fluxa.pro/).

## Visual Assets

This project includes logos and visual assets, including a **Medium-size logo** located at `assets/logo.png`.

## Deployment

The application is deployed using Flask for the web interface and can be scaled with technologies like Gunicorn and Nginx for high-demand environments. It is built to handle a range of real-time text processing tasks, from summarizing lengthy articles to parsing and summarizing complex PDF documents with embedded text.

For more information, please contact the project team.

## License

This project is proprietary and closed-source.
**
# FLUXA AI

Fluxa AI is an innovative website that leverages computer vision technology and advanced language models to create personalized recipes. The platform prompts users to take a photo of their fridge, detects the ingredients within using state-of-the-art image recognition, and generates unique recipes tailored to those ingredients. The process combines cutting-edge deep learning models for visual recognition with powerful natural language processing (NLP) techniques to produce creative, user-specific cooking solutions.

<img src="assets/fluxa.png" alt="Fluxa Logo" width="400"/>

## Features

- **Ingredient Detection**: Utilizes deep learning models to identify various ingredients in user-submitted photos. The system can accurately detect common food items and handle diverse image inputs, even for cluttered fridge shelves.
- **Recipe Generation**: Integrates a fine-tuned LLM (Large Language Model) to produce unique, creative recipes based on detected ingredients, ensuring variety and culinary innovation.
- **Real-Time Processing**: High-speed processing ensures that recipes are generated quickly and accurately, even with complex image data.

## How It Works

1. **Photo Upload**: The user takes a photo of their fridge using a smartphone or other device and uploads it to the Fluxa platform.
2. **Ingredient Detection**: The platform employs computer vision techniques to detect and label ingredients in the image.
3. **Recipe Generation**: Using detected ingredients, the model generates a tailored recipe with detailed instructions.
   
## Advanced Techniques

- **Transformers for NLP**: The recipe generation utilizes a fine-tuned transformer-based model, which is capable of understanding the context of ingredients and suggesting unique recipes.
- **Computer Vision Models**: Incorporates deep learning models like YOLO or EfficientDet for robust image recognition and ingredient classification.

## Access

The application is available online at [Fluxa](https://www.fluxa.pro/).

## Visual Assets

This project includes logos and visual assets, including a **Medium-size logo** located at `assets/logo.png`.

## Deployment

The application is deployed using Flask for the web interface and can be scaled with technologies like Gunicorn and Nginx for high-demand environments. It is built to handle real-time image and text processing tasks, making it versatile for generating recipes based on complex ingredient lists.

## License

This project is proprietary and closed-source.
