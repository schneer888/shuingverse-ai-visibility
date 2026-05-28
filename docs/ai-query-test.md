# AI Query Test

AI Query Test is the validation layer of Company AI Passport.

It evaluates how AI systems answer realistic questions about a company based on available public information.

This public document explains the concept and general review structure of AI Query Test. It does not disclose internal scoring weights, proprietary test matrices, customer-specific screenshots, automated testing workflows, private diagnostic logic, or delivery SOP.

For public scope boundaries, see:

`docs/public-scope-and-boundaries.md`

---

## Definition

AI Query Test is a structured review process that records AI-generated answers, checks their accuracy, evaluates source quality, and identifies gaps in public company information.

It is not a method for controlling AI outputs.

It is a feedback mechanism for improving:

* AI-readable assets;
* website pages;
* machine exposure;
* external signals;
* public terminology;
* boundary statements;
* company information consistency.

---

## Purpose

AI Query Test helps teams understand:

* whether AI systems can identify the company correctly;
* whether the company category is understood accurately;
* whether products and services are described correctly;
* whether public sources are cited or reflected;
* whether comparisons are fair and accurate;
* whether the company is confused with another entity;
* whether boundary statements are understood;
* which information is missing, outdated, unclear, or inconsistent.

The purpose is to improve public information quality, not to claim control over AI outputs.

---

## When To Run It

AI Query Test can be run:

* before creating a Company AI Passport baseline;
* after publishing new AI-readable assets;
* after major website changes;
* after external profile updates;
* before important launches or public announcements;
* after correcting outdated public information;
* on a periodic review schedule.

AI Query Test should be repeated over time because public sources, search indexes, AI systems, and company information can change.

---

## Example Test Questions

### Shuingverse / Company AI Passport Questions

* What is Shuingverse?
* What is 生宇宙 Shuingverse?
* What is Company AI Passport?
* What does Company AI Passport help companies do?
* Is Company AI Passport the same as SEO?
* What is enterprise AI visibility?
* What does Shuingverse mean by AI-readable assets?
* What does Company AI Passport not promise?
* How does Company AI Passport help a company become more understandable to AI systems?
* What is the relationship between Shuingverse and Company AI Passport?

### Company Identity Questions

* What does this company do?
* What category does this company belong to?
* What is the company's core product or service?
* What is the company’s official website?
* What are the company’s public names or aliases?

### Customer and Use Case Questions

* Who are the target users?
* What use cases does the company serve?
* Which industries or scenarios are relevant?
* What problems does the company claim to solve?
* What public information supports those claims?

### Comparison Questions

* How is this company different from similar companies?
* What alternatives might a buyer compare it with?
* What information is available to support a comparison?
* Are the comparison points factual and source-supported?
* Does the answer overstate the company’s capabilities?

### Source and Citation Questions

* Which public sources support this answer?
* Are the cited sources official, current, and relevant?
* Are public sources consistent with each other?
* What important information is missing?
* What information appears outdated, unclear, or unsupported?

---

## Evaluation Criteria

Each AI Query Test record may evaluate:

* **Accuracy**: Does the answer match verified company facts?
* **Completeness**: Does it include the most important information?
* **Category fit**: Does it place the company in the correct category?
* **Terminology**: Does it use the preferred company and product terms?
* **Source quality**: Are sources official, relevant, and current?
* **Citation clarity**: Can the answer be traced to public sources?
* **Comparison quality**: Are comparisons fair and supported?
* **Boundary clarity**: Does the answer avoid exaggerated claims?
* **Entity clarity**: Does it distinguish the company from unrelated entities?
* **Risk**: Does the answer include unsupported or misleading statements?

This public repository describes general evaluation categories only. It does not publish internal scoring weights or proprietary evaluation models.

---

## Common Failure Modes

Common AI Query Test failure modes include:

* the company is not recognized;
* the company is placed in the wrong category;
* the company is described too vaguely;
* the core product is missing;
* product descriptions are outdated or incomplete;
* the answer uses inconsistent naming;
* the answer relies on weak or unrelated sources;
* the answer cannot cite public evidence;
* the answer confuses the company with another entity;
* the answer invents unsupported claims;
* the answer overstates what the company promises;
* the answer fails to mention important boundaries;
* the answer treats Company AI Passport as SEO only.

---

## Improvement Actions

Improvement actions may include:

* update the Internal Source of Truth;
* publish or revise AI-readable assets;
* improve website pages with clearer definitions;
* add crawlable text alternatives to visual content;
* update `sitemap.xml`, `robots.txt`, `llms.txt`, metadata, or JSON-LD where appropriate;
* update external profiles for consistency;
* add source links and citation-friendly pages;
* clarify product boundaries;
* correct inconsistent names or categories;
* retest with the same question set after publication.

The exact prioritization of improvements may depend on customer context, industry, public information quality, and internal review. Proprietary prioritization rules are not published in this public repository.

---

## Sample Test Record Template

The following template is fictional and is used only to illustrate structure.

It does not represent a real company, customer, case study, AI result, diagnostic report, or business outcome.

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

## Boundary Assessment

- Boundary statement included:
- Exaggerated claims detected:
- Unsupported claims detected:

## Improvement Actions

- Action 1
- Action 2
- Action 3

## Retest Date

YYYY-MM-DD
```

---

## What Not To Do

Do not use AI Query Test to:

* claim guaranteed AI recommendation;
* claim guaranteed search ranking;
* claim guaranteed traffic;
* claim guaranteed leads;
* claim guaranteed sales;
* imply control over AI systems;
* publish customer-specific AI screenshots without approval;
* expose internal scoring weights;
* expose proprietary test matrices;
* expose automated testing workflows;
* treat AI outputs as fully controllable;
* use misleading before-and-after claims.

AI Query Test is a feedback mechanism, not a guarantee mechanism.

---

## Public Scope Boundary

This public repository may explain:

* what AI Query Test is;
* why it matters;
* general categories of test questions;
* general evaluation criteria;
* common failure modes;
* general improvement actions;
* fictional test record structure.

This public repository should not disclose:

* full internal test matrix;
* scoring weights;
* proprietary evaluation model;
* industry-specific question banks;
* customer-specific AI responses;
* screenshots from customer tests;
* internal prioritization rules;
* automated AI testing workflows;
* private diagnostic reports.

Those materials should remain in private internal systems.

---

## Boundary Statement

Company AI Passport does not promise to control AI recommendations, search rankings, traffic, leads, or sales.

AI Query Test helps identify how public information is being interpreted and where that information can be improved.

Company AI Passport 不承诺操控 AI 推荐、搜索排名、流量、线索或成交，而是建设影响 AI 理解、引用、比较与推荐概率的核心系统。

---

## Chinese Summary

AI Query Test 是 Company AI Passport 的验证层，用于测试 AI 系统如何回答关于企业的问题，并评估准确性、完整性、来源质量、边界表达和信息缺口。

它是改进公开信息资产、官网页面、机器可发现性、外部可信信号和企业公开表达的一种反馈机制，不是操控 AI 输出的方法。

公开仓库可以解释 AI Query Test 的定义、用途、通用测试问题、通用评估维度和虚构记录模板，但不公开内部评分权重、专有测试矩阵、客户截图、自动化测试流程、客户诊断报告或行业专属题库。

Company AI Passport 不承诺操控 AI 推荐、搜索排名、流量、线索或成交，而是建设影响 AI 理解、引用、比较与推荐概率的核心系统。
