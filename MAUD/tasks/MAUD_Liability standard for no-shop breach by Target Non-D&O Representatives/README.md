# MAUD - Liability standard for no-shop breach by Target Non-D&O Representatives

**Contributor**: Zehua Li (zehuali@stanford.edu)

**Source**: [Atticus Project](https://www.atticusprojectai.org/maud)

**License**: [CC By 4.0](https://creativecommons.org/licenses/by/4.0/)

**Task summary**: Read the following merger agreement and answer: what is the liability standard for no-shop breach by Target Non-D&O Representatives?

**Size (samples)**: 157

## Task Description

This is a multiple-choice task in which the model must select the answer that best characterizes the merger agreement.

## Task Construction

This task was constructed from the [MAUD dataset](https://www.atticusprojectai.org/maud), which consists of over 47,000 labels across 152 merger agreements annotated to identify 92 questions in each agreement used by the 2021 American Bar Association (ABA) [Public Target Deal Points Study](https://www.americanbar.org/groups/business_law/committees/ma/deal_points/). The task is formatted as a series of multiple-choice questions, where given a segment of the merger agreement and a Deal Point question, the model is to choose the answer that best characterizes the agreement as response.

```text
Question: Read the following merger agreement and answer: what is the liability standard for no-shop breach by Target Non-D&O Representatives?
```

```text
Options:
A: Reasonable standard
B: Strict liability
```

## Column names

- `label`: answer key to the question
- `text`: segment of the merger agreement