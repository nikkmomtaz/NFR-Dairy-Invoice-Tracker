## Prototype: AI Prompt
  1. Invoices are uploaded in the AI project thread 10 at a time. (AI limit)
  2. The PDF invoice files are processed, then the AI extracts and returns organized data from the relevant fields (fields have been determined early on in the prompt).
  3. The unreadable PDF files (scanned or picture format) are displayed after the organized data. These files are then manually processed by myself.
     - This data is manually enetered into our NFR tracker excel sheet.
  4. The duplicated files are also labled as duplicate, so that they don't get processed again. (including unreadable files).



## For Potential Implementation:
### Use Case: Upload PDF invoices and Extract data in Table format

**Primary Actor**: Authenticated User  
**Goal**: Upload one or multiple PDF invoices from various vendors and extract structured information 

**Main Flow**:
  1. User visits the upload interface of the web app
  2. User uploads one or multiple invoice PDFs
  3. System extracts relevant fields: Inoive Number, Date, Store Name, Vendor, Product/Dairy Type - QTY x Litres
  
  6. System displays or returns the structured data (JSON/table)
  7. (Optional) User downloads or exports the data to Excel

