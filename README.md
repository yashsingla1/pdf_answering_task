# Pdf_answering_task

### This uses gemini Api to ask questions from pdf
## Usage
1) Upload the pdf file.
2) Replace "ENTER YOUR GEMINI API HERE" with your actual API key
3) Replace "ENTER THE FILE PATH eg. test_sample_1.pdf" with the actual path to your saved PDF file.
4) Enter the Question after running the code.

## Implementation details

1) Text Retrieval Function: The function returns the complete extracted text from the PDF.
2) Request Function: The function returns the text of the generated response.

## Note:
1) The current implementation allows to upload only one pdf file at a time.
2) The prompt is provided so as to provide clear and concise answer.
3) Gemini-1.5-Flash has been used for this task as it is a powerful and versatile language model capable of processing and generating text from a massive context window. This makes it suitable for handling long documents.
   
