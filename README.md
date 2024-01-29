# Diagram-as-Code with Mermaid
This README tutorial will explain how to create class diagrams and sequence diagrams using code. After reading the tutorial, check out the project files for examples of diagram-as-code in practice.

## Why Use Diagram-as-Code?
In a nutshell, there are 3 big reasons:
* It's faster. You type very little in exchange for a well-formatted diagram.
* No separate software; you can make your diagrams in your IDE.
* You can track changes to the diagrams using version control. 
* It's more reusable.

## Requirements 
* VS Code (tested on v1.85.2)
* Markdown Preview Mermaid Support (tested on v1.21.0)
* Mermaid Documentation: https://mermaid.js.org/intro/

## Installation
1. Download VS Code for your OS: https://code.visualstudio.com/download.
2. Follow the VS Code installation guide for your OS:<br>
  * Windows: https://code.visualstudio.com/docs/setup/windows
  * Mac: https://code.visualstudio.com/docs/setup/mac
  * Linux: https://code.visualstudio.com/docs/setup/linux
3. Install the extension Markdown Preview Mermaid Support to render previews of your diagrams: https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid

## Sequence Diagrams
![image](https://github.com/erdietri/DiagramAsCode_Mermaid/assets/37638931/78d9af84-94df-4876-b42e-861377b643e3)
<i>An example sequence diagram illustrating the order of operations for user login</i>
### What is a sequence diagram?
A sequence diagram shows you the flow of operations for a particular use case. They are technical diagrams typically referenced by other engineers/technical folks. More information on this type of UML diagram and its notation: https://www.geeksforgeeks.org/unified-modeling-language-uml-sequence-diagrams/ 
#### Developers
Let's pretend you developed the login feature for your company's app. In order to properly document and explain this feature to the rest of your development team, you might create a sequence diagram. The sequence diagram would illustrate, step-by-step, the communication between client, server, database, etc. 
#### Network Engineers 
While UML diagrams are typically used in software development, the concept of explaining order of operations to other engineers remains the same. You might use this diagram to explain interactions between network devices for educational purposes (i.e. DHCP Handshake), while troubleshooting with tech support, or for explaining network automation.
### Creating a sequence diagram with Mermaid

## Class Diagrams
### What is a class diagram?
### Creating a class diagram with Mermaid
