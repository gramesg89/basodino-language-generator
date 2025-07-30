# BasodinoBot

## 🚀 Try It in Colab
👉 [Open in Colab](https://colab.research.google.com/github/gramesg89/basodino-language-generator/blob/main/notebooks/basodino_bsoup.ipynb)

⚠️ **Project Status: In Progress**

BasodinoBot is a toolkit for generating words in a constructed language (conlang) called *Basodino* using Latin source vocabulary. It includes:

- A Wiktionary scraper for Latin verbs
- A sound change engine that applies phonological transformations based on Old High German 
- IPA handling and rule-based reformulation

## 💡 Purpose

This project blends linguistics, conlang creation, and code. It's a personal language engineering project designed to evolve into a chatbot that can speak and teach Basodino.

## 📂 Contents

- `notebooks/` – Colab-ready notebook with working code
- `data/` – Sample scraped and transformed output  
   - 📊 [Download sample output (CSV)](https://github.com/gramesg89/basodino-language-generator/blob/main/data/basodino_ouput.csv)
    OR [View full output in Google Sheets](https://docs.google.com/spreadsheets/d/1w-zlBhBFOh0FrtZdLvTv6lQNDLmS1sNB4jGkR8DBe48/edit?usp=sharing)
  - Sample of prompt set🧠 [Download full seed prompt set (JSON)](https://github.com/gramesg89/basodino-language-generator/blob/main/data/basodino_seed_examples.json)

## ✅ Current Features

- Scrapes Latin verbs and their IPA from Wiktionary
- Applies a defined set of vowel and consonant shifts
- Outputs transformed IPA strings representing Basodino words

## 🔜 Planned Features

- GUI or CLI for word generation
- Full dictionary builder
- Chatbot interface with grammar rules and translation
- spaCy-style tagging for machine learning and glossing

## 📂 Folders

- `data/`: Latin-to-Basodino transformation examples and IPA logs

## 👨‍💻 Tech Stack

- Python (requests, BeautifulSoup)
- IPA string manipulation
- Linguistic rule application
- Planned: LLM training, chatbot front-end

## 🌍 What Is Basodino?

Basodino is a fictional language inspired by Romance languages and designed with naturalistic sound changes, custom grammar, and a distinct lexicon. It is meant to represent a hypothetical Romance language in which Old High German acts as a substrate under the Vulgar Latin of the 4th century. This project applies these sound changes up until New High German. 

