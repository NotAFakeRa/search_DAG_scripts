# search_DAG_scripts
Scripts to make end-to-end DAG for continuous gravitational wave searches

The overarching script is set_up_search_DAG.sh. 

This initializes a number of important variables and calls a host of other scripts.

This then creates a DAG (Directed Acyclic Graph) within HTCondor's parallel control flow.
The full pipeline is quite complicated:
<img src="https://github.com/NotAFakeRa/search_DAG_scripts/blob/master/BOTR_flowchart20131212.jpg" width="500">
