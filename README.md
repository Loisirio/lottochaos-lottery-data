# Lottery draw results: 36 games, full history

Clean, ready-to-use CSV files with the winning numbers of **36 lotteries** from Europe, North America, Asia and Africa, from the first available draw to today (174,964 rows in total). Maintained by **[Lottochaos](https://lottochaos.com/en/)**, an independent lottery statistics project: pure statistics, no predictions.

- Source page, always up to date: https://lottochaos.com/en/open-data/
- Also on Kaggle: https://www.kaggle.com/datasets/infoloisirio/lottery-draws-36-games-full-history
- Licence: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) – free to use, share and adapt, with attribution "Data: lottochaos.com".

## Files

| Game | Country | File | Rows | First draw | Last draw | Main numbers | Extra columns |
|---|---|---|---:|---|---|---|---|
| Lotto 6 aus 45 | Austria | `data/at_lotto.csv` | 3,693 | 1986-09-07 | 2026-10-16 | 6 of 45 | b1 = Zusatzzahl (bonus) |
| Lotto | Belgium | `data/be_lotto.csv` | 3,528 | 1992-03-28 | 2026-10-17 | 6 of 45 (6 of 42 until 2011) | b1 = bonus number |
| Lotto 6/49 | Canada | `data/ca649.csv` | 4,458 | 1982-06-12 | 2026-10-10 | 6 of 49 | b1 = bonus number |
| Lotto Max | Canada | `data/lottomax.csv` | 1,278 | 2009-09-25 | 2026-10-13 | 7 of 52 (49 until 2019, then 50) | b1 = bonus number |
| Québec 49 | Canada | `data/q49.csv` | 3,030 | 1997-10-01 | 2026-10-10 | 6 of 49 | b1 = complementary number |
| EuroDreams | Europe | `data/ed.csv` | 307 | 2023-11-06 | 2026-10-12 | 6 of 40 | b1 = Dream number |
| EuroMillions | Europe | `data/em.csv` | 1,989 | 2004-02-13 | 2026-10-13 | 5 of 50 | b1–b2 = Lucky Stars |
| Eurojackpot | Europe | `data/ej.csv` | 994 | 2012-03-23 | 2026-10-13 | 5 of 50 | b1–b2 = Euro numbers |
| Keno (FDJ) | France | `data/keno_fr.csv` | 361 | 2025-10-30 | 2026-10-21 | 20 of 70 | slot, multiplier, joker |
| Loto (FDJ) | France | `data/loto.csv` | 1,086 | 2019-11-06 | 2026-10-12 | 5 of 49 | b1 = Chance number |
| KENO | Germany | `data/keno.csv` | 7,966 | 2004-02-02 | 2026-10-20 | 20 of 70 | plus5 = 5-digit Plus 5 number |
| LOTTO 6aus49 | Germany | `data/lotto.csv` | 6,568 | 1955-10-09 | 2026-10-10 | 6 of 49 | b1 = Superzahl (0–9, where available); flag A/B = two draws on the same day |
| Lotto italiano | Italy | `data/it_lotto.csv` | 77,330 | 1939-01-07 | 2026-10-22 | 5 of 90 per wheel | ruota = wheel; numbers in draw order; one row per wheel |
| MillionDAY | Italy | `data/it_md.csv` | 3,180 | 2018-02-07 | 2026-10-22 | 5 of 55 | – |
| SuperEnalotto | Italy | `data/it_se.csv` | 4,288 | 1997-12-03 | 2026-10-22 | 6 of 90 | b1 = Jolly |
| Da Ma Cai 1+3D | Malaysia | `data/dmc.csv` | 3,656 | 2005-01-01 | 2026-10-14 | 4-digit numbers | first, second, third, starter_1–10, consolation_1–10 |
| Magnum 4D | Malaysia | `data/mg4d.csv` | 6,827 | 1985-04-25 | 2026-10-14 | 4-digit numbers | first, second, third, starter_1–10, consolation_1–10 |
| Singapore 4D | Singapore | `data/sg4d.csv` | 2,549 | 2010-04-18 | 2026-10-14 | 4-digit numbers | first, second, third, starter_1–10, consolation_1–10 |
| TOTO | Singapore | `data/toto.csv` | 1,231 | 2014-10-09 | 2026-10-12 | 6 of 49 | b1 = additional number |
| Daily Lotto | South Africa | `data/za_daily.csv` | 2,769 | 2019-03-10 | 2026-10-14 | 5 of 36 | – |
| Lotto Plus 1 | South Africa | `data/za_lp1.csv` | 1,227 | 2015-01-03 | 2026-10-14 | same matrix as SA Lotto | b1 = bonus ball |
| PowerBall | South Africa | `data/za_pb.csv` | 1,227 | 2015-01-02 | 2026-10-13 | 5 of 50 (5 of 45 until 2018) | b1 = PowerBall |
| PowerBall Plus | South Africa | `data/za_pbx.csv` | 1,132 | 2015-12-01 | 2026-10-13 | 5 of 50 (5 of 45 until 2018) | b1 = PowerBall |
| SA Lotto | South Africa | `data/za_lotto.csv` | 1,227 | 2015-01-03 | 2026-10-14 | 6 of 58 (49, then 52 earlier) | b1 = bonus ball |
| Lotto 6/45 | South Korea | `data/kr_lotto.csv` | 1,246 | 2002-12-07 | 2026-10-17 | 6 of 45 | b1 = bonus number |
| Swiss Lotto | Switzerland | `data/ch_lotto.csv` | 1,437 | 2013-01-12 | 2026-10-17 | 6 of 42 | b1 = Glückszahl (lucky number) |
| Lotto Texas | USA | `data/tx_lotto.csv` | 3,503 | 1992-11-14 | 2026-10-24 | 6 of 54 (6 of 50 until 2000) | – |
| Mega Millions | USA | `data/us_mm.csv` | 2,550 | 2002-05-17 | 2026-10-20 | 5 of 70 (range changed in 2005, 2013, 2017) | b1 = Mega Ball |
| Millionaire for Life | USA | `data/us_mfl.csv` | 246 | 2026-02-22 | 2026-10-25 | 5 of 58 | b1 = Millionaire Ball (1–5) |
| New York Lotto | USA | `data/ny_lotto.csv` | 2,621 | 2001-09-12 | 2026-10-24 | 6 of 59 | b1 = bonus |
| Powerball | USA | `data/us_pb.csv` | 2,014 | 2010-02-03 | 2026-10-19 | 5 of 69 (5 of 59 until 2015) | b1 = Powerball |
| Texas Two Step | USA | `data/tx_tts.csv` | 2,655 | 2001-05-18 | 2026-10-22 | 4 of 35 | b1 = bonus ball |
| Cash Five | USA (Texas) | `data/tx_c5.csv` | 8,891 | 1995-10-13 | 2026-10-24 | 5 of 35 (39, then 37 earlier) | – |
| Set For Life | United Kingdom | `data/uk_sfl.csv` | 693 | 2020-02-27 | 2026-10-15 | 5 of 47 | b1 = Life Ball |
| Thunderball | United Kingdom | `data/uk_tb.csv` | 3,992 | 1999-06-12 | 2026-10-16 | 5 of 39 (5 of 34 until 2010) | b1 = Thunderball |
| UK Lotto | United Kingdom | `data/uk_lotto.csv` | 3,215 | 1994-11-19 | 2026-10-14 | 6 of 59 (6 of 49 until Oct 2015) | b1 = bonus ball |

## Format

- UTF-8, comma-separated, one header row, one row per draw (Lotto italiano: one row per draw and wheel).
- `date` is ISO format `YYYY-MM-DD`; `weekday` is `mon` … `sun`.
- Main numbers `n1 … nK` are sorted in ascending order (except Lotto italiano: draw order). Bonus numbers are in `b1`, `b2`.
- 4D games: each prize number is a 4-digit string (leading zeros kept).

## Things to know before analysing

- **Rules change.** Some games changed their number range over time (see the "Main numbers" column: for example UK Lotto went from 6/49 to 6/59 in October 2015, Powerball and Mega Millions changed several times). Split the data by period before testing frequencies.
- **Draws are independent.** Every combination has exactly the same chance in every draw. Our own tests on these files (chi-squared, walk-forward backtests) find no exploitable pattern: hot, cold or "overdue" numbers do no better than chance. See for example [Patterns in chance](https://lottochaos.com/en/articles/patterns-in-chance/) and [Draw machines and ball sets](https://lottochaos.com/en/articles/draw-machines/).
- Results are compiled from officially published sources. If you find an error, please open an issue.

## Ideas

Randomness tests, teaching probability and combinatorics, the gambler's fallacy, number popularity and prize sharing, time-series exercises.

## Citation

> Lottochaos (2026). *Lottery draw results: 36 games, full history* [Data set]. https://lottochaos.com/en/open-data/ – CC BY 4.0.

---
18+ only. Lotteries are games of chance and can be addictive. Help: GamCare (UK) 0808 8020 133, Check dein Spiel (DE) 0800 1 37 27 00, Joueurs Info Service (FR) 09 74 75 13 13.
