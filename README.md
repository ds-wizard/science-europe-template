# Science Europe DMP

This is the DMP template recommended by [Science Europe](https://www.scienceeurope.org) in their [Science Europe Guidance Document](https://www.scienceeurope.org/media/nsxdyvqn/se_guidance_document_rdmps.pdf) designed for use in [Data Stewardship Wizard](https://ds-wizard.org) with *Common Data Stewardship knowledge model*. It applies various rules and synthesizes the text answers from questionnaire replies to relevant questions.


## Usage

This template is available through [DSW Registry](https://registry.ds-wizard.org/templates).


## Issues and Contributing

This document template for DSW is available as open-source via GitHub Repository [ds-wizard/science-europe-template](https://github.com/ds-wizard/science-europe-template), you can [report issues](https://github.com/ds-wizard/science-europe-template/issues) there and fork it for customisations or contributions.


## Changelog

### 1.14.0

- Switch from `wkhtmltopdf` to `weasyprint` for PDF
- Improve styling for PDF and HTML
- Fix (non-)reference data in data summary
- Align data openness with the KM

### 1.13.0

- Adjusted to template metamodel version 11 (released in DSW 3.20.0)
- Add versions overview / change tracker table

### 1.12.0

- Adjusted to template metamodel version 10 (released in DSW 3.12.0)

### 1.11.0

- Adjusted to template metamodel version 9 (released in DSW 3.10.0)

### 1.10.1

- Fix Jinja template nesting error

### 1.10.0

- Compatible with `dsw:root:2.4.0`

### 1.9.0

- Adjusted to template metamodel version 8 (released in DSW 3.8.0)

### 1.8.0

- Adjusted to template metamodel version 7 (released in DSW 3.7.0)

### 1.7.0

- Adjusted to template metamodel version 6 (released in DSW 3.6.0)

### 1.6.0

- Adjusted to template metamodel version 5 (released in DSW 3.5.0)

### 1.5.0

- Adjusted to template metamodel version 4 (released in DSW 3.2.0)

### 1.4.1

- Fix displaying answers related to measured datasets

### 1.4.0

- Adjusted to template metamodel version 3 (released in DSW 2.12.0)

### 1.3.0

- Compatible with `dsw:root:2.3.0`

### 1.2.0

- Adjusted to template metamodel version 2

### 1.1.0

- Compatible with `dsw:root:2.2.0`
- Updated projects and front page as there can be multiple projects specified for a single DMP
- Questions 8, 9, and 10 updated according to DMP Common Standard with dataset - distribution - license hierarchy

### 1.0.0

- Compatible with `dsw:root:2.0.0` and up to `dsw:root:2.1.0`
- Initial version of DMP template created during [ELIXIR BioHackathon Europe 2019](https://www.biohackathon-europe.org)
