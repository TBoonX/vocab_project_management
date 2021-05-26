# Project management vocabulary

![Overview](https://github.com/TBoonX/vocab_project_management/raw/main/overview.png)
This vocabulary is modeling project management in scientific research projects at the level of the application phase and afterwards for the work with tasks.

The above image is an overview about the vocabulary. For a better version please open the image in a new tab or load the ttl file into WebVowl.

## Remarks

Instances of the classes should have a label and a description. For (sub)workpackages, milestones and tasks the short identifier is the Countable instances hasNumber and the label does represent the name.

## External vocabs

### TMO Task Model Ontology

http://www.semanticdesktop.org/ontologies/2008/05/20/tmo/v1.1/
This vocab does model tasks, relations and metadata found when tasks are used to express and track technical work in projects like software creation projects. The concepts are matching common platforms for task management like JIRA or Redmine.
It is complete enough to be used as a whole with the vocab of this repository - namely Task is linked via rdfs:type to it.
For information and visuals please have a look on their webpage.

### DOAP Description of a Project
http://usefulinc.com/ns/doap
DOAP is used to enhance Project with name, description, homepage and homepage information.

### ORG The Organization Ontology
https://www.w3.org/TR/vocab-org/
To express an organization, which every partner of a project is, ORG does provide a way to link members, describe the structure and specific information which could be relevant for projects.

### General ones
foaf <http://xmlns.com/foaf/0.1/>
xsd <http://www.w3.org/2001/XMLSchema#>
time <http://www.w3.org/2006/time#>
dce11 <http://purl.org/dc/elements/1.1/>
