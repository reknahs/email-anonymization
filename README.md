# email-anonymization
Python code for prompt engineering email anonymization with removal of PII

spreadsheet tracking prompt changes: https://docs.google.com/spreadsheets/d/11JkPmPXgS-eLh4ZjXaHmuY-d3s_-BBBZSaC_Uj8ZSog/edit?usp=sharing

Issue List:

1. [FIXED] Anonymization for some newsletter emails takes very long (will remove links in preprocessing and reevaluate)
3. [IN PROGRESS] Labeling is relatively inaccurate (will try allowing for multiple labels)
4. [IN PROGRESS] Json file is wrong a lot of the time (will try getting the tool_calls response + further debugging)

Changes:

1. [COMPLETE] Added subject in beginning of body since it might contain important info
2. [COMPLETE] Implement code for 1000 examples dataset

