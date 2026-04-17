# 🎴 Pokémon TCG Live Deck Builder

> Build competitive Pokémon TCG Live decks instantly from your collection — powered by meta analysis, automation, and smart deck scoring.

---

## 🌐 Live App
👉 https://pokemon-deck-builder-6ud4hm3feyp5yewkkc2kkl.streamlit.app/

---

## ⚡ What is this?

**Pokémon TCG Live Deck Builder** is a smart Streamlit web app that analyzes your card collection and automatically builds **meta-competitive decks** for Standard, Expanded, and GLC formats.

It acts like a personal deck assistant:
- Reads your collection
- Matches it to real meta decks
- Scores what you can actually build
- Exports ready-to-play decks instantly

---

## 🚀 Core Features

### 🏆 Meta Deck Engine
- Standard / Expanded / GLC support
- Tier-ranked decks (S / A+ / A / B+)
- Fully legal 60-card deck validation
- Competitive strategies included

---

### 🧠 Smart AI Deck Builder
- Paste your Pokémon TCG Live collection
- Auto-parses and normalizes cards
- Builds best possible competitive decks
- Scores decks based on:
  - Ownership percentage
  - Meta relevance
  - Core Pokémon availability

---

### 📊 Collection Intelligence
- Fuzzy card matching (fixes naming differences)
- Missing card detection
- Deck completion tracking
- Real-time ownership breakdown

---

### 📤 Instant Export System
- One-click export to Pokémon TCG Live format
- Clean `.txt` download
- Ready for in-game import

---

## 🧠 How It Works

1. Paste your collection export from Pokémon TCG Live  
2. The engine parses and normalizes your cards  
3. It compares your collection to meta decks  
4. It calculates buildability + win potential  
5. You get your **top 4 strongest decks instantly**

---

## 🛠️ Local Setup

### 1. Clone repository
```bash
git clone https://github.com/Jumpzyy/pokemon-deck-builder.git
cd pokemon-deck-builder
2. Create virtual environment
python -m venv venv
3. Activate environment

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
4. Install dependencies
pip install -r requirements.txt
5. Run the app
python -m streamlit run ultimate_pokemon_tool.py
