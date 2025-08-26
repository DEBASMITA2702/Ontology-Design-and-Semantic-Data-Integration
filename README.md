# TAO Assignments – Theory and Applications of Ontologies

## Assignment 1: Ontology Design
- **Task:**  
  We had to pick a domain and create a semantic model using **Description Logic (SROIQ)**. We chose 'StockMarket' domain.  
- **Work Done:**  
  - Wrote a plain text description of the chosen domain.  
  - Identified key knowledge elements to capture in the ontology.  
  - Designed the **TBox ontology** with classes, properties, and DL axioms.  
  - Documented design choices with explanations, motivating examples, and reasoning.  
- **Submission Includes:**  
  - Domain description and knowledge list
  - DL Ontology (TBox)
  - Detailed write-up of design choices and ontology explanation

---

## Assignment 2: XML Data Design
- **Task:**  
Extend Assignment 1 by creating an **XML DTD** for the domain and populating XML data.  
- **Work Done:**  
  - Developed the **DTD schema** to structure data properly.  
  - Populated the XML with representative domain data.  
  - Designed and executed **XPath & XQuery queries** to explore the data.  
- **Submission Includes:**  
  - XML DTD file + description of design.
  - XML data file
  - Set of XPath and XQuery queries with plain English explanations and results

---

## Assignment 3: Ontology Development
- **Task:**  
Build an **OWL Ontology** in Protégé based on the model from Assignment 1.  
- **Work Done:**  
  - Modeled the ontology in **Protégé**.  
  - Checked ontology consistency with a reasoner.  
  - If modifications were made compared to Assignment 1, documented the reasons and changes clearly.  
- **Submission Includes:**  
  - OWL ontology file (consistent)
  - Report (explaining changes, updates, and validation results)

---

## Assignment 4: Inference using OWL
- **Task:**  
Combine XML data (from Assignment 2) with the OWL ontology (from Assignment 3) and perform inference.  
- **Work Done:**  
  - Extracted relevant XML data and converted it into **RDF triples**.  
  - Integrated RDF triples with the OWL ontology.  
  - Performed reasoning using **OWLAPI (Java) or OWLReady (Python)**.  
  - Displayed both **extracted triples** and **inferred triples** after reasoning.  
- **Submission Includes:**  
   - Mapping program (Java/Python)
   - XML data + RDF triples
   - OWL ontology
   - Final results of extracted & inferred triples
   - Readme with run instructions

---

### Note
- Each assignment builds on the previous one: **Ontology Design → XML Modeling → OWL Ontology → Inference & Reasoning.**  
- Tools used include **Description Logic (SROIQ), Protégé, XPath/XQuery, OWLAPI/OWLReady**.  
