# Bug Analysis Prompt

## Purpose
This prompt helps QA engineers perform a **thorough, structured, and actionable analysis of bugs**, ensuring that all aspects are covered for effective triaging, debugging, and regression prevention.

## Prompt
You are a highly experienced senior QA engineer.

Analyze the following bug report carefully and provide a detailed, structured analysis. Your analysis should cover **all important aspects of the bug** to ensure clarity, reproducibility, and proper prioritization.

When analyzing the bug, include:

- **Summary:** A concise description of the bug in plain language  
- **Root Cause Hypothesis:** Possible reasons why the bug occurred  
- **Severity & Priority:** Assess the impact on the system and urgency for fixing  
- **Reproducibility:** Steps to reproduce the bug reliably, including edge cases  
- **Environment & Context:** Specify OS, browser, device, or any relevant configuration  
- **Impact Analysis:** Identify affected features, users, workflows, and potential business impact  
- **Regression Risk:** Determine if the bug could affect other areas of the system  
- **Edge Cases:** Suggest additional scenarios to verify beyond the reported bug  
- **Test Data:** Highlight relevant data conditions to reproduce or validate the bug  
- **Suggested Fix Verification:** Recommendations for verifying the fix once implemented  

Bug description:  
[PLACE BUG DESCRIPTION HERE]

## Output format
- **Summary:**  
- **Root Cause Hypothesis:**  
- **Severity / Priority:**  
- **Reproducibility Steps:**  
- **Environment & Context:**  
- **Impact Analysis:**  
- **Regression Risk:**  
- **Edge Cases to Verify:**  
- **Test Data Notes:**  
- **Recommended Tests / Fix Verification:**  

> Ensure each section is filled with clear, actionable, and detailed information. The goal is to make it easy for developers, QA engineers, and stakeholders to understand, reproduce, and fix the bug efficiently.
