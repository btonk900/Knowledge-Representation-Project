## Deliverables
- [ ] **25% *OWLReady2 Ontology***
  - [ ] Describes concepts *repository*, *user*, *file*, *branch*, *commit*
  - [ ] Define relations:
    - [ ] *Respository* --> set of files, branch ≥ 1
    - [ ] *Branch*      --> has a name and initial commit
    - [ ] *Commit*      --> has a user, a timestamp, a branch, a list of updated files, a message
                        --> at least 1 parent (except initial commit), more than 1 parent is a merge
- [ ] Submission requirements:
  - [ ] A `.owl` file for ontology
  - [ ] A `.py` file for loading knowledge graph into ontology
     
- [ ] **25% *A Knowledge Graph***
  - [ ] Connects ontology to dataset built from repository metadata
  - [ ] SPARQL for the following queries:
    - [ ] *Find all repositories with more than 5 unmerged branches;*
    - [ ] *Find all users who have made concurrent contributions to three or more repositories;*
    - [ ] *Find all commits that are merges;*
    - [ ] *Flag all commit messages containing the text 'security' or 'vulnerability' that have been occured or merged into a given branch;*

- [ ] **15% *A Python Application***
  - [ ] Created using *Flask* or *Command Line* (yet to be determined)
  - [ ] Allows searching and browsing the ontology/knowledge graph
  - [ ] The application should:
    - [ ] Display the data as well as inferred classes and relations;
    - [ ] Provide syntax for *searching* the procedures
    - [ ] Identify any *errors* in the data
