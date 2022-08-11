# EInvoicingSigner
A command prompt application used to serialize and sign tax payers documents before sending the documents to Egyptian Tax Authority. The application reads the invoice JSON file SourceDocumentJson.json and generates the canonical format of the JSON "CanonicalString.txt". The application signs the canonical genrated text and writes the the invoice json with signature into the file FullSignedDocument.json. 

The application reads a configuration xml file tht includes the Token Pin, Token Issuer, and Json invoice to be signed.

