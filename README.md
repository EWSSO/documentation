# Early Warning System Scores Ontology

This project contains documentation related to the EWSSO. The ontology can be located [here](https://github.com/zcilia/ews-ontology).

---

## Example

The `example` directory contains the input and output for calculating various early warning scores using synthetic data from two hypothetical organizations.  The synthetic input data was loaded into a GraphDB instance.  A project utilizing the EWS-Ontology (located [here](https://github.com/jmwhorton/ontosheep)) was then used to query the triplestore (using SPARQL) and calculate the available early warning scores.  The resulting output file contains each score that was able to be calculated based on available data from the two disparate input files.
