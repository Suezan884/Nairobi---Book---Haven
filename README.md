# Book Haven AI Chatbot

An intelligent chatbot designed to help African bookstores automate customer service and enhance book discovery.

**Developed by:** Trizah Nzioka and Susan Otieno

---

## Quick Start

### Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn fuzzywuzzy python-levenshtein ipywidgets
```

### Run the Chatbot

1. Upload `FAQs.csv` and `books.csv` when prompted
2. Execute all cells in `chatbot.ipynb`
3. Interact with the GUI interface

---

## Project Structure

```
├── books.csv              # Book catalog
├── FAQs.csv               # FAQ knowledge base
├── EDA.ipynb              # Data analysis & visualizations
├── chatbot.ipynb          # Main chatbot application
├── Documentation.docx     # Project documentation
└── README.md              # This file
```

---

## Key Features

### Smart Book Search

* Price range queries such as “books under 1000” or “affordable books”
* Multi-layer search: exact → partial → fuzzy matching
* Genre and author discovery

### AI-Powered Intelligence

* Intent classification using Logistic Regression + TF-IDF
* Learns from user feedback
* Tracks performance and response quality

### Data Insights

* Exploratory data analysis
* Visual analytics
* Business intelligence insights for bookstores

---

## Usage Examples

**Book Queries**

* Books by Chimamanda Ngozi Adichie
* How much is Things Fall Apart?
* African Literature books
* Books under 1000 KES

**Store Information**

* Opening hours
* Delivery options
* Payment methods
* Available genres

---

## Special Focus

### Addressing African Business Challenges

* Handles limited local language data
* Supports KES pricing
* Strong focus on African authors and literature
* Works well in low-bandwidth environments

### Educational Value

* Practical NLP implementation
* Demonstrates responsible AI practices
* Culturally aware user experience
* Encourages data-driven decisions

---

## Technical Highlights

* TF-IDF + Logistic Regression intent classifier
* Three-tier book matching algorithm
* Feedback-based learning
* Simple Colab-based graphical interface

---

**Empowering African bookstores through intelligent automation.**
