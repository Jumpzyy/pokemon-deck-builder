# 🎴 Pokémon TCG Live Deck Tool

![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)

A powerful Streamlit web app for **Pokémon Trading Card Game Live** players to analyze collections, build competitive decks, and explore meta strategies across Standard, Expanded, and GLC formats.

---

## 🚀 Live App

👉 https://pokemon-deck-builder-6ud4hm3feyp5yewkkc2kkl.streamlit.app/

---

## ✨ Features

### 🏆 Meta Deck Browser
- Standard format meta decks
- Expanded format archetypes
- Gym Leader Challenge (GLC) decks
- Tier ratings (S / A+ / A / B+)
- Full 60-card legality validation

---

### 🧠 Smart Deck Builder
- Paste your full Pokémon TCG Live collection
- Automatically parses cards
- Builds best possible competitive decks
- Scores decks based on:
  - Card ownership
  - Meta relevance
  - Core Pokémon presence

---

### 📊 Collection Analysis
- Fuzzy card matching (fixes spelling differences)
- Missing card detection
- Ownership tracking per deck
- Deck completion percentage

---

### 📤 Export System
- One-click export to Pokémon TCG Live format
- Clean `.txt` download
- Ready for import into game client

---

### 🔥 Deck Intelligence
- Auto-ranks best decks from your collection
- Shows buildability score (%)
- Predicts deck strength vs meta

---

## 🛠️ How to Run Locally

```bash
pip install streamlit
streamlit run ultimate_pokemon_tool.py
