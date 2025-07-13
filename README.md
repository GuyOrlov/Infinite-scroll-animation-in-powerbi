# 📊 Power BI Infinite Scroll Carousels & Tickers

This repo contains a set of **Power BI measures** that create beautiful, animated infinite scroll carousels and ticker tapes — fully built with **HTML + CSS** inside Power BI DAX measures.

---

## ✅ **What’s included**

- ⚽ **FootballProfileStatsCarousel** — Football player stats in a slick, auto-scrolling format.
- 👥 **ScrollingTeamCard** — Show your team members on a loop, great for office screens.
- 💼 **SalesTeamCarousel** — Highlight top performers with role and sales info.
- 🌍 **MakeupCountryInflationCard** — Compare country inflation rates visually.
- 🛍️ **ProductCarousel** — Show product sales and growth.
- 📈 **KPIHighlightCarousel** — Loop your key metrics in a modern panel.
- 📰 **RetroRadioMessageTicker** — Old-school 1980s radio-style scrolling tape.
- 📺 **CeefaxTicker** — BBC Ceefax–style retro news ticker.
- ⏱️ **SpeedControl** table — Lets users pick the scroll speed via slicer.

---

## 🏗️ **How this works**

- Each measure is **pure DAX** with HTML & CSS inside.
- You use the [HTML Content Viewer](https://docs.powerbi.tips/product/html-content) visual or similar.
- The `SpeedControl` table is a simple `DATATABLE` that lets users pick speeds like `Fast`, `Medium`, `Slow` — this feeds each measure’s `VAR SelectedSpeed`.

---

## 🔗 **Inspiration**

These infinite scroll layouts were inspired by [Temani Afif’s “Infinite Scroll Animation” CodePen](https://codepen.io/t_afif/pen/jOXRGGx).  
I adapted the original concept into **standalone HTML blocks** that work nicely in Power BI as dynamic visuals.

I tidied up the CodePen idea and merged everything into reusable HTML snippets that you can paste into a single DAX measure — **no JavaScript needed**, just HTML and CSS.

---

## 💡 **Usage idea**

- Show these carousels on a big screen in your office or reception area.
- Run a BBC Ceefax–style ticker for fun in a meeting.
- Use the `SpeedControl` slicer to let your audience pick their scroll speed.
- Even works on waiting room screens — imagine it looping for customers!

---

## ⚡ **Credits**

- Original infinite scroll animation by [Temani Afif](https://codepen.io/t_afif)
- Power BI measure version, edits, and README by *[Your Name]*

---

## 🚀 **Try it!**

1. Import the `SpeedControl` table.
2. Add your chosen measure to a **HTML Content Viewer** visual.
3. Add your slicer for speed.
4. Sit back and enjoy your **smooth, infinite scrolling content**!

---

