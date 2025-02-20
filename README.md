# Explanability of symbolic learned programs (Noughts and Crosses) 

## Building minimax database
-canonical_map.m

-data.m

-data.txt (for visualization)

-vdata.txt (for visualization)

-minimax_DB.py (functions for creating database, visualization and conversion to JS)

## Interface V1
### Using database with html via js
Run Python binary_to_JS() in ./minimax_DB.py to generate js usable minimax database

-html_interface/scripts/canonicalMap.js

-html_interface/scripts/data.js

-html_interface/scripts/partitions.js

-html_interface/scripts/partitions15000.js

-html_interface/scripts/partitions15000_parsed.js

### Introduction page
-html_interface/index.html

### Experiment session interface and control
-html_interface/experiment.html

-html_interface/scripts/init.js

-html_interface/scripts/minimax.js

-html_interface/scripts/noughts-and-crosses.js

-html_interface/scripts/questions.js

-html_interface/scripts/utils.js

-html_interface/scripts/variables.js

-html_interface/scripts/explanations.js (explanations in English was pre-computed, 
to re-generate explanations check ./translation.py)

### Submission of record realized through https://driveuploader.com/
Instructions on submission are on html_interface/submission.html

Collector of records needs to have a google account with a usable google drive dir.

## Interface V2
### Experiment session interface and control
-html_interface_v2/index.html

-html_interface_v2/phase1.html

-html_interface_v2/phase2-4.html

-html_interface_v2/submission.html

-html_interface_v2/scripts/~

### Strategy program explanation
**Requirement: SWI prolog V8.0**

--html_interface_v2/explanation

--html_interface_v2/explanation/MIGO

#### Generating explanation
1.locate to 'html_interface_v2/explanation'

2.Start SWI Prolog session in terminal

3.Consult in interactive Prolog mode, `consult(loader).`

4.Examples are given in html_interface_v2/explanation/sl_background_features 
and html_interface_v2/explanation/sl_migo

5.To add targets, `add_target(rule_name).`

6.To start generating explanation, `interpret_program.`


