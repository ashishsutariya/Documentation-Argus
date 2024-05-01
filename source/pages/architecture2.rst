System Overview
======================

**ARGUS: System Architecture and Interaction**

ARGUS employs a modular architecture designed to streamline the literature review process. The system consists of several components that work together seamlessly to provide researchers with efficient tools for document retrieval, assisted reading, and information extraction.

**System Diagram**


.. figure:: /images/arch2.jpg
   :align: center


The system diagram illustrates the flow of data and interactions between different components of ARGUS:

1. **Front End (User Interface)**:
   - Researchers interact with ARGUS through the user interface, which is developed using React.js. 
   - This component facilitates document upload, keyword management, document ranking, assisted reading, and navigation.

2. **Back End (Server-Side)**:
   - The back end, implemented in Express.js, handles user interactions, document processing, and data retrieval.
   - It communicates with the front end and triggers document processing tasks such as PDF-to-HTML conversion and text extraction.

3. **PDF Conversion**:
   - PDF documents uploaded by users are processed using pdf2htmlex for conversion to HTML format.
   - This component ensures that text content within PDFs is accessible for keyword matching and ranking.

4. **Text Extraction**:
   - Text extraction from PDF documents is performed using pdfjs-dist and react-pdf libraries on the front end.
   - Extracted text is utilized for keyword matching and ranking during the literature review process.

**Interaction and Flow**

The interactions and flow within ARGUS can be summarized as follows:

1. **Document Upload and Processing**:
   - Researchers upload PDF documents through the front-end interface.
   - The back end triggers pdf2htmlex for PDF-to-HTML conversion, enabling text extraction and analysis.

2. **Keyword Management and Ranking**:
   - Users manage keywords for document analysis through the front-end interface.
   - ARGUS ranks documents based on keyword relevance, utilizing text extracted from PDFs.

3. **Assisted Reading and Navigation**:
   - Researchers navigate through retrieved documents and highlighted keywords using the front-end interface.
   - Keyword highlighting allows for rapid identification of relevant sections within documents.


The architecture of ARGUS facilitates efficient document retrieval, assisted reading, and information extraction for researchers conducting literature reviews. By leveraging front-end and back-end technologies, along with specialized tools for PDF conversion and text extraction, ARGUS provides a comprehensive platform for researchers to streamline their literature review process.
