# pdf-extract-split-by-search-value
This flow for Microsoft Power Automate allows you to split PDF documents based on a search parameter of content inside of a PDF. Adobe PDF Extract service will take PDF content and return as JSON data which can be used to parse content.

## Files
* ***extract-schema.json***: Contains the JSON schema to use with the Parse JSON action in Microsoft Power Automate.
* ***Invoices_Combined.pdf***: Sample PDF file for testing.
* ***pdf-extract-split-by-search-value.zip***: Flow for Microsoft Power Automate to import.
* ***sample-json.json***: This is the sample JSON structure that is returned from Adobe PDF Extract. This is helpful for learning what content you are looking for. In particularly, you want the _elements_ section.

## Required connectors
* [Adobe PDF Services](https://us.flow.microsoft.com/en-us/connectors/shared_adobepdftools/adobe-pdf-services/)
* [SharePoint](https://us.flow.microsoft.com/en-us/connectors/shared_sharepointonline/sharepoint/)

In order to use Adobe PDF Services, you will need a set of credentials or subscribe.

- [Get Adobe PDF Services Trial](https://documentcloud.adobe.com/dc-integration-creation-app-cdn/main.html )
- [Pricing](https://developer.adobe.com/document-services/pricing/main/)
## Importing flow
To learn how to import a flow into Microsoft Power Automate, see here:
[Read documentation here](https://powerautomate.microsoft.com/en-us/blog/import-export-bap-packages/)

## How to use
For more information, see the blog [here](https://medium.com/adobetech/detect-untagged-pdfs-for-accessibility-with-microsoft-power-automate-85acb970345c).