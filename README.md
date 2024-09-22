README File
Dataset Overview
This repository contains datasets formatted to support the replication of our experiments. 

•Format A (5 Files: Calculator, Easy Mock, JUnit 4, Mini-Tunis, Servlet-API)

In this format, each software system includes the following two files:
    Calls.txt: Each row in this file represents a call dependency relationship between software artifacts.
    Example:
    annotation_HttpConstraint.java annotation_ServletSecurity.java
    This indicates that “annotation_HttpConstraint.java” makes a call to “annotation_ServletSecurity.java.”
    Modules.rsf: This file provides the ground truth for the software systems, detailing the membership of artifacts within modules.
    Example:
    contain annotation annotation_HttpConstraint.java
    This signifies that “annotation_HttpConstraint.java” belongs to the “annotation” module, where "contain" is the keyword.

•Format B (Mozilla Firefox Modules)

The folders pertaining to Mozilla Firefox include three files:
    CDG.txt: This file presents an adjacency matrix that depicts the relationships between components.
    FileNames.txt: This file lists the names of artifacts in the same order as they appear in the adjacency matrix.
    FilePathNames.txt: This file provides the modularization as determined by the developers.

•Format C (21 Files: Modulizer, acqCIGNA, bison, boxer, cia, cia++, ciald, compiler, graph10up193, graph10up49, grappa, incl, ispell, lab4, lucent, mtunis, nos, rcs, spdb, star, swing)

In this format, each file consists of rows that display call dependency relationships.
Example:
AbstractAction SwingPropertyChangeSupport
This indicates that AbstractAction calls SwingPropertyChangeSupport.

Conclusion
We hope this dataset and its accompanying documentation will facilitate your research and experimentation. If you have any questions or require further information, please feel free to reach out.

