# Currency Exchange Rate Data Analysis

A beginner-friendly data analysis project that retrieves live currency exchange rates from an API, converts the data into a structured format using Pandas, and allows interactive currency searches.

## Project Overview

This project fetches the latest exchange rate data based on **USD (United States Dollar)** from an online API and transforms the JSON response into a clean **Pandas DataFrame** for analysis.

Users can search for exchange rates by entering a **currency code** or **partial keyword** in an interactive command-line loop.

This project demonstrates practical skills in:

- API integration
- Data extraction
- Data transformation
- Data analysis with Pandas
- Interactive Python scripting

---

## Features

✅ Fetches live exchange rate data from an external API

✅ Converts JSON response into a structured Pandas DataFrame

✅ Supports interactive currency search

✅ Allows partial keyword matching

✅ Displays results in a readable table format

✅ Exit command support (`quit` or `exit`)

---

## Technologies Used

- Python
- Pandas
- Requests
- API Integration

---

## Project Structure

```text
data-analysis-with-SQL/
│── sql
│── README.md
│── .venv/
```

---

## API Source

Exchange rate data is retrieved from:

`https://api.exchangerate-api.com/v4/latest/USD`

Base currency: **USD**

---

## Installation

Install required dependencies:

```bash
pip install pandas requests
```

Or if using a virtual environment:

```bash
/workspaces/data-analysis-with-SQL/.venv/bin/pip install pandas requests
```

---

## How to Run

Run the script:

```bash
/workspaces/data-analysis-with-SQL/.venv/bin/python sql
```

---

## Example Usage

Input:

```text
Enter currency code: EUR
```

Output:

```text
Currency    Rate
EUR         0.92
```

Partial search example:

Input:

```text
Enter currency code: JP
```

Output:

```text
Currency    Rate
JPY         156.20
```

Exit program:

```text
quit
```

or

```text
exit
```

---

## Skills Demonstrated

This project showcases beginner-level data engineering and data analysis concepts:

- API Requests
- JSON Parsing
- Data Cleaning
- Data Transformation
- Pandas DataFrame Operations
- User Input Handling
- Interactive Search Logic

---

## Future Improvements

Potential enhancements for this project:

- Add historical exchange rate tracking
- Store results in SQL database
- Create trend analysis charts
- Add currency comparison feature
- Build dashboard visualization
- Automate daily data collection

---

## Learning Purpose

This project was created as part of a learning journey into:

**Data Analysis → Data Engineering → Automation**

It serves as a foundation for building larger ETL and analytics projects.
