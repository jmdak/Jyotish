
# 🌟 Jyotish GPT – AI-Powered Vedic Astrology Engine

**Jyotish GPT** is a fully dynamic, Python-based Vedic astrology engine that:
- Calculates **birth charts (D1), divisional charts (D9, D10, etc.)**
- Computes **Vimshottari Mahadasha & Antardasha** timelines till 120 years
- Detects classical **Yogas** and **Doshas** with exact reasoning
- Generates **timeline-based predictions**
- Produces **PDF reports** and optionally integrates with Google Docs / Zapier

---

## 🔧 Technologies Used
- ✅ Swiss Ephemeris (`pyswisseph`)
- ✅ Python 3
- ✅ ReportLab, Pandas, Flask
- ✅ Markdown-ready output

---

## ⚙️ Core Modules

### 📍 `birth_chart_calculator.py`
- Sidereal planetary longitudes using Lahiri Ayanamsa
- Ascendant (Lagna) & Moon Nakshatra + Pada
- Whole Sign House (WSH) mapping

### 📍 `dasha_calculator.py`
- Full Vimshottari Dasha calculation up to 2098
- Moon Nakshatra balance and timeline

### 📍 `yoga_dosha_engine.py`
- Detection of:
  - Rajyogas, Dhan Yogas, Vipreet Rajyogas
  - Neechabhanga Rajyoga
  - Manglik, Kaal Sarp, Pitra, Grahan, Kemadruma, Shrapit Doshas
  - Gajakesari, Budha-Aditya Yogas
- Each rule logs "Detected" ✅ or "Not Detected" ❌ with reasoning

### 📍 `timeline_predictor.py`
- Predicts career, health, relationships, spiritual trends
- Uses Dasha sequence + yoga/dosha activation
- Narrative output per period

---

## 📦 Output
- ✅ Planet-wise Chart
- ✅ Lagna, Nakshatra Summary
- ✅ Mahadasha & Antardasha Timeline
- ✅ Full Yoga/Dosha Table
- ✅ Timeline-based Predictions
- ✅ PDF Export (via ReportLab)

---

## 🧪 Test Example

```python
# Sample Input
Name: Anurag Kapoor
DOB: 2 September 1978
TOB: 23:45 IST
Place: Delhi, India
```

Results:
- Lagna: Taurus ♉︎
- Moon: Leo, Purva Phalguni Nakshatra
- Active Dasha: Rahu (2015–2033)
- Yogas: Kemadruma Dosha ✅
- Kaal Sarp: ❌ Not Detected

---

## 🚀 Installation

```bash
git clone https://github.com/your-username/jyotish-gpt.git
cd jyotish-gpt
pip install -r requirements.txt
python main.py
```

---

## 📁 Project Structure

```
jyotish-gpt/
├── app/
│   ├── birth_chart_calculator.py
│   ├── dasha_calculator.py
│   ├── yoga_dosha_engine.py
│   ├── timeline_predictor.py
│   └── report_exporter.py
├── data/  # Swiss Ephemeris files
├── output/  # PDF reports
├── main.py
├── requirements.txt
```

---

## 📘 License
MIT

---

## 🙏 Acknowledgments
- Classical Sources: BPHS, Saravali, Phaladeepika
- Astronomy by Swiss Ephemeris
- Assisted by OpenAI ChatGPT for narrative generation
