# FetchXML

A collection of FetchXML queries for use with Microsoft Dataverse and Dynamics 365.

## What is FetchXML?

FetchXML is Microsoft's XML-based query language for retrieving data from Dataverse. Queries can be run via the Dataverse Web API, the XrmToolBox FetchXML Builder, or pasted directly into Advanced Find in model-driven apps.

Useful tools:
- [XrmToolBox - FetchXML Builder](https://www.xrmtoolbox.com/plugins/Cinteros.Xrm.FetchXmlBuilder/)
- [Dataverse Web API docs](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/retrieve-and-execute-predefined-queries)

## Queries

| File | Description |
|------|-------------|
| FindHiddenPPSolutions | Retrieves hidden Power Platform solutions from a Dataverse environment — useful for auditing or troubleshooting managed solution layers |

## Usage

1. Copy the FetchXML content from the file.
2. Paste into **XrmToolBox FetchXML Builder** to run against your environment, or
3. Use the XML as the etchXml parameter in a Dataverse Web API request.