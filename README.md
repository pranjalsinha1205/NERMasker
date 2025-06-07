# 🛡️ Named Entity Redactor - spaCy Project

This is a small but meaningful project in my NLP learning journey — aimed at **masking named entities** (like names, places, organizations) in real-world news data.

## 🔍 Objective

Use **spaCy**'s Named Entity Recognition to anonymize sensitive information in the following columns:

- 📰 Headline
- 📄 Short Description
- ✍️ Authors

The goal is to simulate a **text anonymization** or **preprocessing pipeline** for downstream tasks such as:
- Privacy protection
- Bias mitigation
- Ethical NLP applications

---

## 🛠️ Tech Stack

- Python 🐍
- spaCy (en_core_web_sm model)
- Pandas for data handling

---

## 🧪 Example

| Type | Headline | Description | Author |
|------|----------|-------------|--------|
| **Original** | Barack Obama visits UN | Barack Obama discussed climate change. | John Smith |
| **Masked** | [PERSON] visits [ORG] | [PERSON] discussed climate change. | [PERSON] |

---

## 📬 Github link

https://github.com/pranjalsinha1205/NERMasker
