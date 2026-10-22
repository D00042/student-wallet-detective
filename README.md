# Student Wallet Detective

An interactive dashboard that asks one question: where does a student's month go?

Filter by city, study level and month. The KPIs, weekly trend, category ranking, weekday pattern and written findings are all recomputed from the filtered rows. It includes a median alongside the mean, a weekend-versus-calendar comparison, and a CSV export.

## Data note

All 640 purchases are generated in the page by a seeded random generator (seed 2026). The data is fictional and is not connected to a database. The generator's assumptions (weekend food, September shopping) are documented in the page, so the findings describe those assumptions rather than real behaviour.

To use real data, replace the generator in `index.html` with rows shaped as `date, city, level, category, amount`.

## Run or publish

Open `index.html` in a browser. To publish, enable GitHub Pages (Settings, Pages, branch `main`, folder `/root`).
