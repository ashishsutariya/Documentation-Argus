Technologies Used
=====================
.. .. figure:: /images/arguslogo.png
..    :align: center
..    :align: left
..    :height:10

**ARGUS: Automated Research Guidance & User Support**



.. figure:: /images/sarchi.jpg
   :align: center



Front End:
----------

The user interface of ARGUS is developed using React.js, a popular JavaScript library for building interactive user interfaces. React.js allows for the creation of reusable UI components, enabling a modular and efficient development process.

Back End:
---------

ARGUS utilizes Express.js, a fast, unopinionated, minimalist web framework for Node.js, as the back-end framework. Express.js simplifies the development of robust web applications by providing a range of features for handling HTTP requests, routing, and middleware integration.

PDF Conversion:
---------------

PDF documents uploaded by users are converted to HTML format using pdf2htmlex, a command-line tool for converting PDF files to HTML. This conversion process enables efficient text extraction and analysis of document content within ARGUS.

Text Extraction:
----------------

Text extraction from PDF documents is performed on the front end using pdfjs-dist and react-pdf libraries. pdfjs-dist provides functionalities for parsing and rendering PDF documents, while react-pdf offers components for displaying PDF content within React applications.

Data Storage:
-------------

ARGUS adopts a temporary storage approach for document data, where uploaded documents are temporarily stored in server folders during processing. This temporary storage simplifies initial implementation and management of document data within the system.


The technologies and components utilized in ARGUS play a crucial role in streamlining the literature review process for researchers. By leveraging frameworks like React.js and Express.js, along with specialized tools for PDF conversion and text extraction, ARGUS offers a robust and efficient platform for conducting literature reviews.


.. figure:: /images/techs.jpg
   :align: center
