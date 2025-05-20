# 🧬 PubMed Pharma Paper Finder

## 📖 Overview

This command-line Python tool allows you to query **PubMed** for scientific articles and filter the results to include only those with **at least one author affiliated with a pharmaceutical or biotechnology company**. The extracted data is compiled into a structured **CSV file** for easy analysis and reporting.

---

## 🎯 Features

* 🔍 Full support for **PubMed’s advanced query syntax** for precise searches.
* 🧑‍🔬 Automatically detects authors from **non-academic institutions**, with a focus on **biotech and pharma affiliations**.
* 📊 Extracts and formats key metadata:

  * **PubMed ID**
  * **Article Title**
  * **Publication Date**
  * **Non-academic Author(s)**
  * **Company Affiliation(s)**
  * **Corresponding Author Email**
* 📁 Exports results to a clean, structured **CSV file**.
* 🛠 Offers command-line options for help, debugging, and file output customization.

---

## 🧰 Command-Line Usage

### 🔧 Options

* `-h`, `--help`: Show usage instructions.
* `-d`, `--debug`: Enable detailed debug logging.
* `-f`, `--file`: Specify the name of the output CSV file.

---

### ▶ Example Usage

```bash
python -m get_paper_list.fetcher "cancer immunotherapy" -f results.csv --debug

```


