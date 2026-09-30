I'm a data scientist at BTG Pactual, working on machine learning in production: pipelines,
real-time APIs and LLM evaluation on AWS. M.Sc. from TU Darmstadt.

Outside work I build tools I use myself. Before that, I wrote a thesis on keeping energy data
private.

<p align="center">
  <a href="https://github.com/PedroLFerraz/ankigen"><img src="assets/ankigen.png" width="49%" alt="AnkiGen: a daily LLM pipeline that writes Anki cards that fit the deck you already study"></a>
  <a href="https://github.com/PedroLFerraz/TTSing"><img src="assets/ttsing.png" width="49%" alt="TTSing: reads your EPUBs, PDFs and news aloud, highlighting every word as it's spoken"></a>
  <a href="https://github.com/PedroLFerraz/DifferentialPrivacy"><img src="assets/differential-privacy.png" width="49%" alt="Differential Privacy: M.Sc. thesis at TU Darmstadt and Poli-USP on anonymizing household gas data"></a>
</p>

- **[AnkiGen](https://github.com/PedroLFerraz/ankigen)**: every morning a GitHub Actions run syncs my Anki
  collection, writes the day's cards with one LLM, fact-checks them with a second, drops what I already
  know by embedding similarity, and syncs the rest back to my phone. Idempotent stages over a DuckDB
  warehouse, with an Airflow DAG for the same stages.
- **[TTSing](https://github.com/PedroLFerraz/TTSing)**: an Android reader for books, PDFs and news that
  highlights each word as it's spoken, with neural voices that run on the phone. Kotlin and Jetpack Compose.
- **[DifferentialPrivacy](https://github.com/PedroLFerraz/DifferentialPrivacy)**: my master's thesis, on
  how much privacy household gas-consumption data can be given before it stops being useful. Python,
  OpenDP and a Flask app to try the methods.

[LinkedIn](https://www.linkedin.com/in/pedro-lopes-ferraz)
