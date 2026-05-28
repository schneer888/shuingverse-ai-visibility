# AI Query Test

AI Query Test is the validation layer of Company AI Passport.

It evaluates how AI systems answer realistic questions about a company based on available public information.

## Definition

AI Query Test is a structured review process that records AI-generated answers, checks their accuracy, evaluates source quality, and identifies gaps in public company information.

It is not a method for controlling AI outputs. It is a feedback mechanism for improving AI-readable assets, website pages, machine exposure, and external signals.

## Purpose

AI Query Test helps teams understand:

- Whether AI systems can identify the company correctly
- Whether the company category is understood accurately
- Whether products and services are described correctly
- Whether public sources are cited or reflected
- Whether comparisons are fair and accurate
- Which information is missing, outdated, or inconsistent

## When To Run It

AI Query Test can be run:

- Before creating a Company AI Passport baseline
- After publishing new AI-readable assets
- After major website changes
- After external profile updates
- Before important launches or public announcements
- On a periodic review schedule

## Example Test Questions

Company identity:

- What does this company do?
- What category does this company belong to?
- What is the company's core product or service?

Customer and use case:

- Who are the target users?
- What use cases does the company serve?
- Which industries or scenarios are relevant?

Comparison:

- How is this company different from similar companies?
- What alternatives might a buyer compare it with?
- What information is available to support a comparison?

Source and citation:

- Which public sources support this answer?
- Are the cited sources official, current, and relevant?
- What important information is missing?

## Evaluation Criteria

Each AI Query Test record should evaluate:

- Accuracy: Does the answer match verified company facts?
- Completeness: Does it include the most important information?
- Category fit: Does it place the company in the correct category?
- Terminology: Does it use the preferred company and product terms?
- Source quality: Are sources official, relevant, and current?
- Citation clarity: Can the answer be traced to public sources?
- Comparison quality: Are comparisons fair and supported?
- Risk: Does the answer include unsupported or misleading statements?

## Common Failure Modes

Common AI Query Test failure modes include:

- The company is not recognized.
- The company is placed in the wrong category.
- Product descriptions are outdated or incomplete.
- The answer uses inconsistent naming.
- The answer relies on weak or unrelated sources.
- The answer cannot cite public evidence.
- The answer confuses the company with another entity.
- The answer invents unsupported claims.

## Improvement Actions

Improvement actions may include:

- Update the Internal Source of Truth.
- Publish or revise AI-readable assets.
- Improve website pages with clearer definitions.
- Add crawlable text alternatives to visual content.
- Update external profiles for consistency.
- Add source links and citation-friendly pages.
- Retest with the same question set after publication.

## Sample Test Record Template

```markdown
# AI Query Test Record

## Test Date

YYYY-MM-DD

## AI System Tested

Name and version, if available

## Query

What does Example Company Alpha do?

## Response Summary

Short summary of the AI-generated answer.

## Accuracy Assessment

- Correct:
- Incorrect:
- Missing:
- Unclear:

## Source Assessment

- Sources cited:
- Source quality:
- Missing sources:

## Improvement Actions

- Action 1
- Action 2
- Action 3

## Retest Date

YYYY-MM-DD
```

## Boundary Statement

Company AI Passport does not promise to control AI recommendations, search rankings, traffic, leads, or sales. AI Query Test helps identify how public information is being interpreted and where that information can be improved.

## 中文摘要

AI Query Test 是 Company AI Passport 的验证层，用于测试 AI 系统如何回答关于企业的问题，并评估准确性、完整性、来源质量和信息缺口。它是改进公开信息资产的反馈机制，不是操控 AI 输出的方法。
