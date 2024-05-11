# PDF Splitter
Some lecture notes are really long, making it difficult to read and navigate through. So I created this tool to split your PDF into smaller PDFs based on a page range you can define. 

# How to Use
`split_pdf(input_pdf, output_pdf, page_numbers)` 

- `input_pdf`: Filename / filepath of your input PDF
- `output_pdf`: Filename / filepath of your output PDF
- `page_numbers`: Desired page range to extract. For example, you can use `page_numbers = [1, 3, '5-33', 55, '88-90']` to select pages 1, 3, 5 to 33, 55, and 88-90. 

# Example
```
page_numbers = [1,'3-4','6-10']
split_pdf('lecture notes 1.pdf', 'summary.pdf', page_numbers)
```
