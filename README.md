
🔱 Jyotish GPT — Advanced Vedic + Lal Kitab Astrology Engine


⸻

Jyotish GPT is a full-scale, bilingual (Hindi-English) Astrology Platform that generates hyper-detailed astrological reports based on classical Vedic Shastras and Lal Kitab. It supports dynamic Mahadasha timelines, divisional charts (D1–D16), real-time transit analysis, yoga/dosha detection, Lal Kitab forecasts, remedies including Tantra insights, and personalized Q&A functionality — all packaged in beautiful PDF or Google Docs exports.

⸻

🧿 Features
	•	🔭 Accurate Planetary Calculations (Swiss Ephemeris).
	•	📈 Vimshottari Dasha — 120 years Mahadasha/Antardasha/Pratyantar.
	•	🛕 Divisional Charts — D1 to D16 (Navamsa, Dasamsa, etc.).
	•	🔮 Yoga and Dosha Detection — Rajyogas, Manglik, Kaal Sarp, Pitra Dosha.
	•	🛕 Lal Kitab Forecast — Yearly and Monthly Varshphal till 25 years.
	•	📅 Transit Predictions — Jupiter, Saturn, Rahu/Ketu, Sade Sati analysis.
	•	🧿 Remedies Engine — Mantras, Gemstones, Totkas.
	•	🔱 Tantra Remedies — Beej Mantras, Yantras, Deity Upasana.
	•	🌙 Nakshatra Deity Remedies — Secret upayas based on Janma Nakshatra.
	•	🔢 Numerology Analysis — Birth, Destiny, Name Numbers.
	•	📚 Spiritual Evolution Timeline — Life Phase Mapping (Karma, Bhakti, Jnana).
	•	🔍 Ask Your Kundli — AI-backed Q&A from your birth data.
	•	🧾 PDF and Google Docs Export — Professional, printable reports.
	•	📊 Admin Dashboard — Monitor Reports, Errors, Q&A Logs.

⸻

🛠️ Technologies Used

Layer	Tech Stack
Backend	Python (Flask), Swiss Ephemeris
Frontend	React, Vite, TailwindCSS
Data	JSON, SQLite
Export	Markdown → WeasyPrint / Google Docs API
Deployment	Replit


⸻

🗂️ Project Structure

jyotish-gpt/
├── backend/
│   ├── app.py
│   ├── astrology_calculations.py
│   ├── dasha_calculator.py
│   ├── divisional_chart_generator.py
│   ├── transit_engine.py
│   ├── yoga_detection.py
│   ├── dosha_detection.py
│   ├── lal_kitab_engine.py
│   ├── remedies_engine.py
│   ├── tantra_remedies_engine.py
│   ├── nakshatra_remedies_engine.py
│   ├── monthly_forecast_generator.py
│   ├── personality_analysis.py
│   ├── spiritual_timeline.py
│   ├── ask_question_engine.py
│   ├── report_generator.py
│   ├── google_docs_api.py
│   ├── pdf_exporter.py
│   ├── models.py
│   ├── utils/
│   │   ├── geo_location.py
│   │   ├── ayanamsa.py
│   │   ├── timezone_converter.py
│   ├── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── App.tsx
│   │   ├── components/
│   │   │   ├── InputForm.tsx
│   │   │   ├── KundliChart.tsx
│   │   │   ├── DivisionalCharts.tsx
│   │   │   ├── DashaTimeline.tsx
│   │   │   ├── PredictionsSection.tsx
│   │   │   ├── RemediesSection.tsx
│   │   │   ├── TantraSection.tsx
│   │   │   ├── MonthlyForecastSection.tsx
│   │   │   ├── SpiritualTimeline.tsx
│   │   │   ├── AskQuestion.tsx
│   │   │   ├── ReportViewer.tsx
│   │   │   ├── AdminDashboard.tsx
│   ├── vite.config.js
│   ├── tailwind.config.js
│   ├── package.json
├── data/
│   ├── lal_kitab_grammar.json
│   ├── yogas_data.json
│   ├── doshas_data.json
│   ├── remedies_data.json
│   ├── tantra_data.json
│   ├── nakshatra_deity_remedies.json
│   ├── numerology_data.json
│   ├── monthly_forecast_rules.json
├── database/
│   ├── jyotish_gpt.db
│   ├── schema.sql
├── sample_reports/
│   ├── SAMPLE_REPORT.md
│   ├── sample_report_output.pdf
├── README.md


⸻

📚 Key Features Explained

🔭 Planetary & House Calculations
	•	Accurate sidereal longitudes using Swiss Ephemeris.
	•	House Cusp calculations.
	•	Lagna (Ascendant) based on Place, Date, Time.

📅 Dasha & Timeline Predictions
	•	Full 120-year Vimshottari Mahadasha-Antardasha.
	•	Monthly breakdowns with nested dashas.
	•	Gantt chart visualization.

🔮 Yogas and Doshas Detection
	•	BPHS Yogas (Gajakesari, Neechabhanga, Vipreet Rajyoga, etc.).
	•	Doshas: Manglik, Kaal Sarp, Pitra, Grahan, Kemadruma.

🛕 Lal Kitab Forecast
	•	Planet-House effects (grammar based).
	•	25 years of Yearly and Monthly Forecasts.

🧿 Remedies Engine
	•	Personalized:
	•	Mantras (Sanskrit + Hindi Transliteration).
	•	Gemstone Recommendations.
	•	Totkas and Upayas.
	•	Priority Scheduler for remedies (Start date, Duration, Urgency).

🔱 Tantra and Mystical Remedies
	•	Beej Mantras.
	•	Yantra Energization.
	•	Deity-based Remedies.
	•	Nakshatra Deity Secret Remedies (Hidden Upayas).

🌙 Numerology and Spiritual Timeline
	•	Birth Number, Destiny Number, Name Number Predictions.
	•	Suggested Life Phases: Karma Yoga → Bhakti Yoga → Jnana Yoga.

❓ Ask Your Kundli (Q&A)
	•	Type your question and get a dynamic astrology-backed answer.

📄 Reporting
	•	Full Markdown-based report with:
	•	Charts (Lagna, Navamsa, Dasamsa).
	•	Tables (Planetary Positions, Dasha Timeline, Remedies).
	•	Graphs (Strength Graphs, Dasha Gantt Chart).
	•	Life Area Wise Predictions.
	•	Exportable as:
	•	📄 PDF (WeasyPrint / ReportLab).
	•	📝 Google Docs (via Docs API).

⸻

🚀 Quick Start

1. Clone the Repository

git clone https://github.com/your-username/jyotish-gpt.git
cd jyotish-gpt

2. Setup Backend

cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py

3. Setup Frontend

cd frontend
npm install
npm run dev

4. Access
	•	Frontend: http://localhost:3000
	•	Backend API: http://localhost:5000

⸻

📦 Deployment
	•	Replit-ready.
	•	Railway.app Deployment guide.
	•	Dockerfile (coming soon!).

⸻

📚 References
	•	📖 Brihat Parashara Hora Shastra (BPHS)
	•	📖 Jataka Parijata
	•	📖 Saravali
	•	📖 Phaladeepika
	•	📖 Lal Kitab (1941 Edition + Later)
	•	📖 KP Astrology Texts
	•	📖 Astrological Yogas by B.V. Raman

⸻

🧿 License

MIT License

⸻

🤝 Contributing

PRs, suggestions, and new ideas are welcome! Please create an issue or submit a pull request.

⸻

👨‍💻 Author

Built with 🧡 by Your Name

⸻

📝 Sample Report Preview


⸻

📫 Contact

For consulting or API integration: 📧 your.email@example.com

⸻

🔥 Support This Project

If you found this project helpful, please ⭐ star the repo and spread the word!

⸻

🌟 Live Demo

coming soon!

