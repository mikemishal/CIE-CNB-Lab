# CIE CNB

Build a connected Microsoft 365 Copilot workflow for a fictional banking scenario. You will follow one professional through a multi-application task, carrying each output forward instead of starting over at each application boundary.

In this lab, you are Taylor Brooks, a product operations manager at Cornerstone National Bank (CNB). CNB is preparing to improve its small business onboarding experience. You have a Word briefing note, an Excel performance workbook, and one hour to prepare a readiness-review recommendation.

You'll perform four tasks:

- Extract the business issue from a briefing note using **Copilot in Word**
- Analyze onboarding performance data using **Copilot in Excel**
- Validate the recommendation using **Analyst**
- Draft a final recommendation memo using **Copilot in Word**

> **NOTE:** Sample prompts are provided to help you get started. Feel free to personalize them for your environment. If Copilot does not deliver the result you need, refine your prompt and try again. Keep all outputs preliminary and subject to human review.

## Duration

20 minutes

## Required files

- [Small business onboarding readiness brief](https://github.com/mikemishal/CIE-CNB-Lab/blob/main/small-business-onboarding-metrics.xlsx)
- [Small business onboarding metrics workbook](https://github.com/mikemishal/CIE-CNB-Lab/blob/main/small-business-onboarding-metrics.xlsx)

## Required applications

- Microsoft Word
- Microsoft Excel
- Microsoft 365 Copilot Chat
- Analyst

## Task 1: Extract the business issue from the Word briefing note

Using **Copilot in Word**, summarize the readiness-review brief. This creates the business context you will carry into Excel and Analyst.

**Steps**:

- Open the small business onboarding readiness brief in Word.
- Review the scenario, stakeholder feedback, and decision needed.
- Use Copilot in Word to summarize the business issue.
- Ask Copilot to separate confirmed feedback from assumptions.
- Save the output as your **Issue summary**.

**Sample Prompt**:

```text
Summarize this small business onboarding readiness brief for a product operations manager.

Identify the main friction points, affected teams, likely customer impact, and decisions needed for the readiness review. Separate confirmed feedback from assumptions and keep the summary concise.
```

> **TIP:** If the summary is too general, ask Copilot to organize the response by stakeholder group: relationship managers, operations, digital banking, branch staff, and leadership.

## Task 2: Analyze the onboarding data in Excel

Using **Copilot in Excel**, analyze the onboarding metrics workbook to identify which customer segments have the highest onboarding friction.

**Steps**:

- Open the small business onboarding metrics workbook in Excel.
- Review the segment-level metrics and the friction summary sheet.
- Use Copilot to identify patterns across onboarding time, rework rate, missing documentation, digital activation, and customer satisfaction.
- Ask Copilot to cite the metrics that support its findings.
- Save the output as your **Data findings**.

**Sample Prompt**:

```text
Analyze this small business onboarding workbook for Cornerstone National Bank.

Identify which customer segments have the highest onboarding friction, what metrics support that conclusion, and which operational issue should be addressed first. Consider average days to onboard, rework rate, missing documentation rate, beneficial ownership exceptions, digital activation, and customer satisfaction. Label assumptions and call out data limitations.
```

> **NOTE:** Do not accept a recommendation unless Copilot explains which metrics support it.

## Task 3: Validate the recommendation with Analyst

Using **Analyst**, challenge the issue summary and data findings before drafting the recommendation. This step helps you identify unsupported claims, missing context, and the strongest evidence-based recommendation.

**Steps**:

- Open Analyst from Microsoft 365 Copilot Chat.
- Provide the **Issue summary** from Task 1.
- Provide the **Data findings** from Task 2.
- Ask Analyst to validate the strongest drivers of onboarding friction.
- Save the output as your **Validation notes**.

**Sample Prompt**:

```text
Validate this small business onboarding analysis for Cornerstone National Bank.

Use the Issue summary and Data findings below. Look for the strongest drivers of onboarding friction, possible data limitations, unsupported claims, and the recommendation most likely to improve customer satisfaction fastest. Separate source-backed findings, calculated observations, assumptions, and human decision points.

[Paste Issue summary]

[Paste Data findings]
```

> **TIP:** Ask Analyst to recommend one primary intervention and one secondary intervention, then explain what evidence supports each.

## Task 4: Draft the recommendation memo in Word

Using **Copilot in Word**, turn the issue summary, data findings, and validation notes into a one-page recommendation memo for the readiness review.

**Steps**:

- Open Word.
- Start a new blank document.
- Paste or reference your **Issue summary**, **Data findings**, and **Validation notes**.
- Ask Copilot to draft a one-page recommendation memo.
- Review the memo and confirm it separates evidence, assumptions, recommendations, risks, owner roles, and success measures.

**Sample Prompt**:

```text
Draft a one-page recommendation memo for CNB's small business onboarding readiness review.

Use the Issue summary, Data findings, and Validation notes as source material. Include: situation, evidence, primary recommendation, secondary recommendation, implementation steps, owner roles, risks, and success measures. Keep the tone concise and executive-ready. Add "DRAFT - PRELIMINARY ANALYSIS - REQUIRES HUMAN REVIEW" at the top.
```

> **NOTE:** The final memo should not imply final approval. It should identify what a human reviewer must decide before implementation.

## Completion criteria

You have completed the lab when you have:

- One issue summary from the Word briefing note.
- One data findings summary from Excel.
- One validation note from Analyst.
- One draft recommendation memo in Word.
- At least one place where output from an earlier task was reused in a later task.

## Reflection

Answer these questions after the lab:

1. Which output became the most useful input for the next application?
2. Where did Copilot need more context or a refined prompt?
3. How did Analyst improve or challenge the recommendation?
4. What would you change before using this workflow with real bank data?
