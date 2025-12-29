# SkillCorner X PySport Analytics Cup
This repository contains the submission template for the SkillCorner X PySport Analytics Cup **Analyst Track**. 
Your submission for the **Analyst Track** should be on the `main` branch of your own fork of this repository.

Find the Analytics Cup [**dataset**](https://github.com/SkillCorner/opendata/tree/master/data) and [**tutorials**](https://github.com/SkillCorner/opendata/tree/master/resources) on the [**SkillCorner Open Data Repository**](https://github.com/SkillCorner/opendata).

## Submitting
Make sure your `main` branch contains:

1. A single Jupyter Notebook in the root of this repository called `submission.ipynb`
    - This Juypter Notebook can not contain more than 2000 words.
    - All other code should also be contained in this repository, but should be imported into the notebook from the `src` folder.


or,


1. A single Python file in the root of this repository called `main.py`
    - This file should not contain more than 2000 words.
    - All other code should also be contained in this repository, but should be imported into the notebook from the `src` folder.

or, 


1. A publicly accessible web app or website written in a language of your choice (e.g. Javascript)

    - Your code should follow a clear and well defined structure.
    - All other code should also be contained in this repository.
    - The URL to the webapp should be included at the bottom of the read me under **URL to Web App / Website**


2. An abstract of maximum 300 words that follows the **Analyst Track Abstract Template**.
3. Add a URL to a screen recording video of maximum 60 seconds that shows your work. Add it under the **Video URL** Section below. (Use YouTube, or any other site to share this video).
4. Submit your GitHub repository on the [Analytics Cup Pretalx page](https://pretalx.pysport.org)

Finally:
- Make sure your GitHub repository does **not** contain big data files. The tracking data should be loaded directly from the [Analytics Cup Data GitHub Repository](https://github.com/SkillCorner/opendata). For more information on how to load the data directly from GitHub please see this [Jupyter Notebook](https://github.com/SkillCorner/opendata/blob/master/resources/getting-started-skc-tracking-kloppy.ipynb).
- Make sure the `submission.ipynb` notebook runs on a clean environment, or
- Provide clear and concise instructions how to run the `main.py` (e.g. `streamlit run main.py`) if applicable in the **Run Instructions** Section below.
- Providing a URL to a publically accessible webapp or website with a running version of your submission is mandatory when choosing to submit in a different language then Python, it is encouraged, but optional when submitting in Python.

_⚠️ Not adhering to these submission rules and the [**Analytics Cup Rules**](https://pysport.org/analytics-cup/rules) may result in a point deduction or disqualification._

---

## Analyst Track Abstract Template (max. 300 words)
#### Introduction
SkillCorner has revolutionized the industry by providing high-fidelity physical data that offers strong tactical context. However, for a scout under time pressure, the primary challenge lies in efficiently extracting actionable recruitment insights from these deep datasets. This project presents a Scouting Dashboard designed to maximize the value of SkillCorner’s unique aggregates while making complex data accessible to non-technical stakeholders. By streamlining the ability to filter players based on specific physical requirements and benchmarking them against positional averages, the tool translates raw tracking data into a clear recruitment strategy.
#### Usecase(s)
The dashboard enables users to execute pinpoint searches tailored to their team's philosophy. For example, a club seeking a dominant 1v1 winger can filter for high Explosivity Scores, a composite of top speed and acceleration frequency, to ensure a distinct physical advantage in duels. Furthermore, by isolating TIP (Team In Possession) Sprinting, scouts can quantify a player's proactive intent to exploit space behind the defensive line. Conversely, defensive profiles can be screened using OTIP (Opposition In Possession) HSR and High Deceleration Counts to identify "high-press" specialists who possess the reactive agility to disrupt opponent build-up. These applications ensure that physical data is always viewed through a tactical lens.
#### Potential Audience
The primary audience includes Heads of Recruitment and Data Scouts within clubs. The tool serves as a high-performance filtering layer, allowing recruitment teams to screen the Australian League (or any SkillCorner-covered league) based on rigorous physical standards. By ensuring that "eyes-on" scouting is prioritized for players already physically validated by the data, the tool optimizes departmental resources. A significant extension could be the integration of SkillCorner’s Dynamic Player Events, which would layer tactical intelligence over these physical profiles, creating a multi-dimensional screening tool that further enhances data-driven recruitment.

---

## Video URL
https://youtu.be/KkwwFl5YG8E

---

## Run Instructions
To run this project locally, follow these steps:

Clone the repository:

Bash

git clone https://github.com/BigR-2000/analytics_cup_analyst.git
cd analytics_cup_analyst
Install dependencies:

Bash

pip install -r requirements.txt
Launch the dashboard:

Bash

streamlit run main.py

---

## [Optional] URL to Web App / Website

https://skillcorner-x-pysports-scoutingtool.streamlit.app/
