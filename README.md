⚖️ AI-Legal-Documentation-Assistant

This Python script implements a simple, console-based application to match user-entered case details to relevant legal statutes from a local CSV file. It leverages natural language processing techniques, specifically **string similarity algorithms** and a **dictionary of legal synonyms**, to find matches that go beyond simple keyword comparison.

🚀 Key Features

* **Law Type Filtering:** Allows users to narrow down the search by a specific law type (e.g., 'Criminal', 'Civil').
* **Semantic Matching:** Uses the `difflib.SequenceMatcher` to find similarity between words, enabling matches even with slight spelling variations.
* **Synonym Generation:** Generates variations of law descriptions by substituting complex legal terms with simpler meanings (e.g., replacing 'contravenes' with 'violates'), greatly increasing the chance of a match against user input.
* **Stop Word Removal:** Cleans both the law description and the user's case input by removing common words (`is`, `and`, `the`, etc.) before comparison.
* **Jurisdictional Reference:** Generates a Google Search link for the matching law's jurisdictional reference for easy external lookup.
* **CSV Output:** Saves all matching results to an `output.csv` file.

## ⚙️ Requirements & Installation

### Prerequisites

To run this script, you must have Python installed.

### Dependencies

This project relies on the **Pandas** library and the standard Python `difflib` and `itertools` modules.

```bash
pip install pandas
