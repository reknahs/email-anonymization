# email-anonymization
Python code for prompt engineering email anonymization with removal of PII

spreadsheet tracking prompt changes: https://docs.google.com/spreadsheets/d/11JkPmPXgS-eLh4ZjXaHmuY-d3s_-BBBZSaC_Uj8ZSog/edit?usp=sharing

Bugs as of now:

1. Anonymization for some newsletter emails takes very long (will remove links in preprocessing and reevaluate)
2. Labeling is relatively inaccurate (will try allowing for multiple labels)
3. Json file is wrong a lot of the time (will try getting the tool_calls response + further debugging)

