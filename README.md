# email-anonymization
Python code for prompt engineering email anonymization with removal of PII

spreadsheet tracking prompt changes: https://docs.google.com/spreadsheets/d/11JkPmPXgS-eLh4ZjXaHmuY-d3s_-BBBZSaC_Uj8ZSog/edit?usp=sharing

Issue List:

1. [DONE] Anonymization for some newsletter emails takes very long (will remove links in preprocessing and reevaluate)
3. [DONE] Labeling is relatively inaccurate (will try allowing for multiple labels)
4. [DONE] Json file is wrong a lot of the time (will try getting the tool_calls response + further debugging)
5. [IN PROGRESS] tool_calls is None even for code in documentation, need to find updated code to ensure it is not None

Changes:

1. [COMPLETE] Added subject in beginning of body since it might contain important info
2. [IN PROGRESS] Implement code for 1000 examples dataset

Labeling Accuracies:
1. Refunds - 1/1
2. Cancellations - 5/5 (all were both refund and cancellation)
3. Newsletters - 2/5 (other 3 were OCS)
4. OCS - 4/5 (other was newsletter)
5. Orders - 2/3 (other was only shipping/tracking email)
