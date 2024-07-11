# email-anonymization
Python code for prompt engineering email anonymization with removal of PII

spreadsheet tracking prompt changes: https://docs.google.com/spreadsheets/d/11JkPmPXgS-eLh4ZjXaHmuY-d3s_-BBBZSaC_Uj8ZSog/edit?usp=sharing

Issue List:

1. [DONE] Anonymization for some newsletter emails takes very long (will remove links in preprocessing and reevaluate)
3. [DONE] Labeling is relatively inaccurate (will try allowing for multiple labels)
4. [IN PROGRESS] Json file is wrong a lot of the time (will try getting the tool_calls response + further debugging)

Changes:

1. [COMPLETE] Added subject in beginning of body since it might contain important info
2. [COMPLETE] Implement code for 1000 examples dataset

Labeling Accuracies:
Refunds - 1/1
Cancellations - 5/5 (all were both refund and cancellation)
Newsletters - 2/5 (other 3 were OCS)
OCS - 4/5 (other was newsletter)
Orders - 2/3 (other was only shipping/tracking email)
