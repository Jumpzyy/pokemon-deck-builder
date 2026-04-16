# 🎴 Pokémon Deck Builder (Streamlit)

A smart Streamlit-based tool that converts your raw Pokémon TCG collection into playable 60-card decks automatically.

It parses messy card lists, detects Pokémon, Trainers, and Energy, then builds structured decks based on simple meta logic and type synergy.

---

## 🔥 Features

- Paste your full card collection (messy format supported)
- Automatically detects:
  - Pokémon
  - Trainers
  - Energy
- Builds competitive-style 60 card decks
- Type-based deck construction (Fire, Water, Grass, etc.)
- Auto core Pokémon selection (EX / V / GX / Mega priority)
- Basic legality validation (max 4 copies rule)
- Generates **ready-to-import Pokémon TCG Live deck list**
- Clean Streamlit UI

---

## 🚀 How to Run Locally

### 1. Install requirements
```bash
pip install streamlit
streamlit run ultimate_pokemon_tool.py
