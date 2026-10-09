# Netflix Movies & Series Dashboard | Tableau

An interactive Tableau dashboard that explores Netflix's catalogue of **8,800+ movies and series**: what content is on the platform, which genres and ratings dominate, and how its reach spreads across countries.

> **Dashboard preview:** add a screenshot here, e.g. `![Netflix Dashboard](images/dashboard.png)`
>
> **Live dashboard:** [View on Tableau Public](https://public.tableau.com/your-link) *(replace with your link)*

---

## Objective

Turn raw Netflix catalogue data into a clear, interactive view that answers questions such as:

- How is the catalogue split between **Movies** and **TV Series**?
- Which **genres** appear most often?
- How are titles distributed across **ratings** (maturity categories)?
- Which **countries** produce or distribute the most content?
- How has content added to Netflix changed **over time**?

*(Edit this list to match the exact questions your dashboard answers.)*

---

## Dataset

- **Source:** [Netflix Movies and Series on Kaggle](https://www.kaggle.com/datasets/debayank2024/netflix-movies-and-series) by debayank2024
- **Size:** 8,800+ titles
- **Coverage:** genres, ratings, and global reach of Netflix movies and series

Please check the dataset page for the exact column list and licence before reuse.

---

## Dashboard Contents

| Visual | What it shows |
|---|---|
| [Visual name, e.g. Movies vs TV Shows] | [e.g. share of the catalogue by type] |
| [Visual name, e.g. Top Genres] | [e.g. most frequent genres] |
| [Visual name, e.g. Ratings Breakdown] | [e.g. titles per maturity rating] |
| [Visual name, e.g. Content by Country] | [e.g. map of where titles come from] |
| [Visual name, e.g. Titles Added Over Time] | [e.g. trend by year] |
| [Filters / Actions] | [e.g. Type, Year, Country, Genre] |

*(Replace the rows above with the sheets in your dashboard.)*

---

## Key Insights

*(Fill in with what you found. Examples of the style that works well:)*

- [e.g. Movies make up X% of the catalogue, and TV series make up Y%.]
- [e.g. The most common genre is ___, followed by ___.]
- [e.g. Most titles carry a ___ rating, which suggests the catalogue targets ___.]
- [e.g. ___ and ___ are the top two content-producing countries.]
- [e.g. Content additions peaked in ___ and then ___.]

---

## Data Preparation

*(Describe what you did before building the visuals. Delete anything that doesn't apply.)*

- Checked and handled missing values in [columns, e.g. country, rating].
- Split multi-value fields (such as genres or countries) so each value could be counted separately.
- Converted date fields into proper date types, and created year and month fields.
- Created calculated fields for [e.g. content type share, decade, duration in minutes].

---

## How to Open the Workbook

1. Download the repository (**Code → Download ZIP**) or clone it:
   ```bash
   git clone https://github.com/lucky-katiyar/Netflix-dashboard.git
   ```
2. Open `[your-file-name].twbx` in **Tableau Desktop** or **Tableau Public**.
3. If Tableau asks for the data source, point it to the dataset file in the `data/` folder.

---

## Repository Structure

```
Netflix-dashboard/
├── README.md
├── [your-file-name].twbx      # Tableau packaged workbook
├── data/                      # dataset (or link to the Kaggle source)
└── images/                    # dashboard screenshots
```

*(Adjust to match what you actually uploaded.)*

---

## Skills Demonstrated

Data cleaning | Calculated fields | Dashboard design | Interactive filters and actions | Data storytelling | Tableau

---

## Tools

Tableau (Desktop / Public) | Kaggle dataset | GitHub

---

## Author

**Lucky Katiyar**
[GitHub](https://github.com/lucky-katiyar) | [LinkedIn](https://www.linkedin.com/in/your-profile)

---

## Acknowledgements

Dataset by [debayank2024](https://www.kaggle.com/datasets/debayank2024/netflix-movies-and-series) on Kaggle.
