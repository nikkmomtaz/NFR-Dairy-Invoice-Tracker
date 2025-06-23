## Prototype: AI Prompt
1. 10 invoices at a time are uploaded in the AI project thread.
2. The PDF invoice files are processed, then the AI extracts and returns organized data from the relevant fields (fields have been determined early on in the prompt).
   - This data is manually enetered into our NFR tracker excel sheet.
4. The unreadable PDF files (scanned or picture format) are displayed after the organized data. These files are then manually processed by myself.
5. The duplicated files are also labled as duplicate, so that they don't get processed again. (including unreadable files).


For future implementation:
## Use Case: Upload PDF invoices and Extract data in Table format

**Primary Actor**: Authenticated User  
**Goal**: Upload one or multiple PDF invoices from various vendors and extract structured information (e.g.,)
**Main Flow**:
  1. User visits the upload interface of the web app
  2. User uploads one or multiple invoice PDFs
  3. System extracts relevant fields:
  
  6. System displays or returns the structured data (JSON/table)
  7. (Optional) User downloads or exports the data to Excel

