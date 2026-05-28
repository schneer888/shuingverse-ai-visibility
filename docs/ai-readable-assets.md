# AI-readable Assets

AI-readable assets are public information assets designed to be easy for AI systems, search systems, and human readers to parse, cite, compare, and reuse.

They are a core part of Company AI Passport.

This public document explains asset types and principles. It does not disclose internal generation prompts, scoring models, customer templates, delivery SOP, automation workflows, or private implementation details.

For public scope boundaries, see:

`docs/public-scope-and-boundaries.md`

---

## Definition

An AI-readable asset is a structured public document or page that presents verified company information in a clear, stable, machine-accessible format.

Good AI-readable assets are:

* publicly accessible;
* text-based or text-forward;
* structured with clear headings;
* consistent in terminology;
* citation-friendly;
* focused on facts, definitions, use cases, and comparisons;
* updated when company information changes;
* aligned with the company’s official website and public positioning.

---

## Why They Matter

AI systems often synthesize answers from available public information. If a company only publishes fragmented, visual, vague, or inconsistent content, AI systems may have limited reliable material to interpret.

AI-readable assets help reduce ambiguity by making company information easier to:

* discover;
* parse;
* summarize;
* cite;
* compare;
* validate;
* reuse in relevant contexts.

The goal is not to manipulate AI systems, but to improve the quality, consistency, transparency, and accessibility of public company information.

---

## Human-readable vs AI-readable

Human-readable content is designed primarily for people. It may use visual hierarchy, brand language, images, short slogans, interactive layouts, or campaign-driven messaging.

AI-readable content is designed to make information explicit. It uses structured text, stable definitions, consistent labels, and clear source context.

The two formats should support each other.

A company website can remain human-friendly while also linking to structured AI-readable assets that provide clearer public reference material for search systems, AI systems, partners, and evaluators.

---

## Common Asset Types

Common AI-readable assets include:

* company profile;
* product or service profile;
* founder or team brief;
* category definition;
* use-case page;
* FAQ document;
* comparison document;
* public methodology document;
* source list;
* glossary;
* machine-readable index;
* public knowledge file;
* AI Query Test question set;
* public boundary statement.

These assets should be based on verified public information, not private strategy or unsupported claims.

---

## Recommended Formats

Recommended formats include:

* Markdown documents;
* plain text documents;
* HTML pages with crawlable text;
* structured FAQ pages;
* JSON-LD structured data, when appropriate;
* schema markup, when appropriate;
* `llms.txt`;
* `sitemap.xml`;
* `robots.txt`;
* plain-text documentation indexes;
* public repository documentation;
* stable official website pages.

PDFs can be useful for human review, but important facts should also exist in crawlable text formats.

Image-heavy or JavaScript-only materials should not be the only public source for important company information.

---

## Best Practices

Good AI-readable assets should:

* start from an approved Internal Source of Truth;
* use clear headings and short sections;
* define the company, product, category, users, and use cases directly;
* keep terminology consistent across documents;
* link related assets together;
* include dates or version context when helpful;
* separate verified facts from opinions or future plans;
* avoid unsupported claims;
* make pages public and stable when they are intended for AI visibility;
* include the official website link;
* include boundary statements where relevant;
* avoid keyword stuffing;
* avoid vague marketing slogans without factual definitions;
* remain consistent with the company’s website and external profiles.

---

## What Not To Do

Avoid:

* publishing vague slogans without factual definitions;
* hiding key information in images or inaccessible layouts;
* using inconsistent product names or category labels;
* creating unsupported comparisons;
* adding fictional customers, metrics, certifications, or partnerships;
* publishing private business plans or sensitive customer data;
* publishing internal scoring models or delivery SOP;
* exposing private prompt chains or automation workflows;
* claiming control over AI recommendations, rankings, traffic, leads, or sales;
* treating AI-readable assets as a shortcut for guaranteed AI visibility;
* using AI-readable documents to make claims that are not supported by public sources.

---

## Public Scope Boundary

This public repository may explain:

* what AI-readable assets are;
* why they matter;
* what public formats may be useful;
* how they relate to Company AI Passport;
* how they support clearer public information;
* how they connect to website pages, external signals, and AI Query Test.

This public repository should not disclose:

* customer-specific asset drafts;
* internal prompt chains;
* automated generation workflows;
* scoring weights;
* customer diagnostic templates;
* private delivery SOP;
* real customer before-and-after examples;
* private implementation logic.

Those materials should remain in private internal systems.

---

## Example Structure

The following example is fictional and is used only to illustrate structure.

It does not represent a real company, customer, case study, business result, or performance claim.

```markdown
# Company Profile

## Company Name

Example Company Alpha

## Category

Enterprise workflow software

## Description

Example Company Alpha provides workflow software for operations teams that need to organize recurring internal processes.

## Target Users

- Operations teams
- Department managers
- Internal process owners

## Products or Services

- Workflow documentation
- Task coordination
- Internal approval tracking

## Use Cases

- Standard operating procedure management
- Recurring task coordination
- Approval process tracking

## Public Sources

- Official website
- Public documentation
- Company profile page

## Boundary Statement

This example is fictional and is used only to demonstrate structure.
```

---

## Boundary Statement

AI-readable assets improve the quality and accessibility of public company information.

They do not promise to control AI recommendations, search rankings, traffic, leads, or sales.

Company AI Passport 不承诺操控 AI 推荐、搜索排名、流量、线索或成交，而是建设影响 AI 理解、引用、比较与推荐概率的核心系统。

---

## Chinese Summary

AI-readable assets 指面向 AI 搜索、智能体、搜索系统和人类读者的公开结构化资料。

它们通过清晰标题、稳定术语、可引用文本、公开链接和机器可读取格式，帮助 AI 更准确地理解、引用、比较和复用企业信息。

常见形式包括 Markdown 文档、TXT 文档、HTML 页面、FAQ 页面、JSON-LD 结构化数据、`llms.txt`、`sitemap.xml`、`robots.txt`、公开知识文件和公开方法论文档。

公开仓库可以解释 AI-readable assets 的定义、作用、格式和公开原则，但不公开内部 prompt、评分模型、客户模板、交付 SOP、自动化工作流或真实客户数据。

Company AI Passport 不承诺操控 AI 推荐、搜索排名、流量、线索或成交，而是建设影响 AI 理解、引用、比较与推荐概率的核心系统。
