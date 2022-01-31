OntoATMProject is a n3 (https://www.w3.org/TeamSubmission/n3/) project which allow us verification matching among software components. The goal of Component-Based Software Engineering (CBSE) is the development of software systems in terms of an assembly of pre-fabricated software components, Verification is an important task that ensures contract conformance among components. The objective of this project is to perform semantic verification between components using semantic web technologies using ontologies and semantic queries with the SPARQL language (https://www.w3.org/TR/rdf-sparql-query/).

To exemplify this project, an application for an automated teller machine (ATM) is considered as a case study, which consists of 5 software components: Atm, Bank, Card, Printer and UserConsole.

The full project consists of:

1.- An core ontology for software components "ontocoresc.n3"

2.- Atm.IDL and its corresponding instance file in n3 => Atm.n3

3.-Bank.IDL and its corresponding instance file in n3 => Bank.n3

4.-Card.IDL and its corresponding instance file in n3 => Card.n3

5.-Printer.IDL and its corresponding instance file in n3 => Printer.n3

6.-UserConsole.IDL and its corresponding instance file in n3 => UserConsole.n3 

Remarks: For each IDL File it was neccesary transforming in an n3 file using Moctezuma prototype.

For testing: the entire project is assembled in a single ontological file "OntoATMProject.n3" that you need to download and the SPARQL queries: "Query1-Semantic-Operators.sparql" and "Query2-SyntacticOperators.sparql" to carry out the tests.

Author: Dr. Francisco Edgar Castillo Barrera

e-mail: ecastillo@uaslp.mx

Last revision: December 2019

