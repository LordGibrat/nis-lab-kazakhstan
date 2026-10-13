# NIS Lab

NIS Lab is a browser-based Kazakh-language practice platform for students preparing for the entrance selection process to the 7th grade of NIS schools.

**[Open the live platform →](https://lordgibrat.github.io/nis-lab-kazakhstan/)**

![NIS Lab home page](preview.png)

No server, account, or API key is required. The app can also be downloaded and opened directly from `index.html` in Chrome or Edge.

## What the prototype includes

- Separate student profiles with browser-local progress.
- An 18-question diagnostic across six subject areas.
- Focused practice sets and mixed-subject practice.
- Rule-based selection that prioritises weaker topics and unanswered questions.
- Immediate explanations and an error-review loop.
- A 24-question, 25-minute mini mock exam with subject-level results.
- A parent view with accuracy, activity statistics, and CSV/JSON export.
- Links to official and supplementary preparation resources.

The bank contains 127 manually prepared tasks: 75 authored questions and 52 checkable numerical variants in mathematics and quantitative reasoning. The “adaptive” selection is a transparent rule system based on answer history; it does not use a generative model or paid API.

## Scope and limitations

NIS Lab is an independent practice tool, not an official NIS product or exam. NIS is not affiliated with the project, and the statistics describe activity inside this app rather than predicting admission outcomes.

Progress is stored in the browser’s `localStorage`. Export a backup from the parent section before switching browsers or clearing site data.

## Sources and design

- [NIS sample entrance tasks](https://www.nis.edu.kz/ru/page/konkurstyq-irikteu-tapsyrmalarynyn-ulgileri)
- [NIS Pedagogical Measurements Centre course](https://www.academia.kz/ru/course/38)
- [Official NIS practice test](https://www.nis.edu.kz/ru/page/baiqau-testileui)

The interface composition was informed by educational product references; the layouts and graphics in this repository were created for NIS Lab.
