import fitz  

def extract_text_from_pdf(pdf_path):
    document = fitz.open(pdf_path)
    
    for page_num in range(document.page_count):
        page = document.load_page(page_num)  
        text = page.get_text("text")  
        print(f"Page {page_num + 1}:\n{text}\n{'-'*40}")

pdf_path = r'C:\Users\Lenovo\Desktop\Send Email Bot\Dependencies\report.pdf'

extract_text_from_pdf(pdf_path)
