## Deliverables
- [ ] **25% OWLReady2 Ontology**
  - [ ] Describes concepts *repository*, *user*, *file*, *branch*, *commit*
  - [ ] Define relations:
    - [ ] *Respository* --> set of files, branch ≥ 1
    - [ ] *Branch*      --> has a name and initial commit
    - [ ] *Commit*      --> has a user, a timestamp, a branch, a list of updated files, a message
                        --> parent ≥ 1 (except initial commit), is a merge if 
