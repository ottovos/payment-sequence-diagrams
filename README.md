# payment-sequence-diagrams
Collection of sequence diagrams for payment using mermaid you can use and adopt the way you like. Why Mermaid? Easy to adjust and adopt.


Source of data:
The purpose of the sequence diagrams is to get a quick understanding on how payment brands operate functionally. 
All data is based on publicly available infromation on the internet.

How to Visualize mermaid sequence diagrams:
- In Atom install the Mermaid preview packge (https://atom.io/packages/atom-mermaid)
- In Confluence install mermaid Macro

Mermaid:
- https://mermaidjs.github.io/#/README



Sofort:
Documentation: https://www.sofort.com/integrationCenter-eng-DE/content/view/full/2513/
Synopsis:
- Authentication: username + password (API access key)
- XML content type
- Merchant defines abort and succes url 
- Usually a merchant will use an acquirer/PSP. In the sequence diagram the position of this PSS would be Between the merchant and Sofort (actually FinTecSystems) 
