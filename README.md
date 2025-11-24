⚖️ AI-Legal-Documentation-Assistant

A simple, console-based Python application that matches user-entered legal case details to relevant statutes from a local database. It leverages Natural Language Processing (NLP) techniques—specifically string similarity algorithms and synonym expansion—to find relevant laws even when exact keywords are missing.

🚀 Key Features

Law Type Filtering: Narrow down searches by specific legal categories (e.g., 'Criminal', 'Civil') to improve accuracy.

Semantic Matching: Utilizes difflib.SequenceMatcher to calculate similarity between words, detecting matches despite spelling variations or typos.

Synonym Generation: automatically expands the search by substituting complex legal jargon with simpler synonyms (e.g., interpreting 'contravenes' as 'violates'), significantly increasing match probability.

Stop Word Removal: Filters out common noise words (e.g., is, and, the) from both the statute descriptions and user input to focus on key legal terms.

Jurisdictional Reference: Generates direct Google Search links for specific laws to facilitate quick external research.

CSV Output: Exports all identified matches to a standardized output.csv file for record-keeping.

⚙️ Requirements

Prerequisites

Python 3.x installed on your machine.

Dependencies

This project relies on the following external library:

pandas

Note: The script also uses difflib and itertools, which are included in the standard Python library and do not require separate installation.
This project relies on the **Pandas** library and the standard Python `difflib` and `itertools` modules.

```bash
pip install pandas
