# 📊 Power BI Infinite Scroll Carousels & Retro Tickers

Welcome to my **Power BI Infinite Scroll & Ticker Pack** — a creative way to bring **dynamic scrolling content** into your reports using pure HTML + CSS **inside DAX measures**.

---

## ✅ **What’s inside**

<p align='center'>
  <img src="img/SalesTeamCarousel.png" alt="Scrolling Team Card" style="max-width: 100%;">
</p>
- 👥 **Team Cards** — Meet your team with the `ScrollingTeamCard`.

<p align='center'>
  <img src="img/FootballProfileStatsCarousel .png" alt="Football Profile Stats Carousel" style="max-width: 100%;">
</p>
- ⚽ **Football Stats** — Loop through player profiles with the `FootballProfileStatsCarousel`.

<p align='center'>
  <img src="img/SalesTeamCarousel.png" alt="Sales Team Carousel" style="max-width: 100%;">
</p>
- 💼 **Sales Team Carousel** — Show top performers with the `SalesTeamCarousel`.

<p align='center'>
  <img src="img/MakeupCountryInflationCard.png" alt="Makeup Country Inflation Card" style="max-width: 100%;">
</p>
- 🌍 **Inflation Carousel** — Compare countries visually with the `MakeupCountryInflationCard`.

<p align='center'>
  <img src="img/ProductCarousel.png" alt="Product Carousel" style="max-width: 100%;">
</p>
- 🛍️ **Product Carousel** — Highlight products with the `ProductCarousel`.

<p align='center'>
  <img src="img/CustomerTestimonialCarousel.png" alt="Customer Testimonial Carousel" style="max-width: 100%;">
</p>
- ⭐ **Customer Testimonial Carousel** — Show customer reviews with the `CustomerTestimonialCarousel`.

<p align='center'>
  <img src="img/KPIHighlightCarousel.png" alt="KPI Highlight Carousel" style="max-width: 100%;">
</p>
- 📈 **KPI Highlight Carousel** — Big KPIs on loop with the `KPIHighlightCarousel`.

<p align='center'>
  <img src="img/CompanyTimelineCarousel.png" alt="Company Timeline Carousel" style="max-width: 100%;">
</p>
- 🏢 **Company Timeline Carousel** — Your company’s story with the `CompanyTimelineCarousel`.

<p align='center'>
  <img src="img/RetroRadioMessageTicker.png" alt="Retro Radio Message Ticker" style="max-width: 100%;">
</p>
- 📻 **Retro Radio Message Ticker** — 1980s broadcast style with the `RetroRadioMessageTicker`.

<p align='center'>
  <img src="img/CeefaxTicker.png" alt="Ceefax Ticker" style="max-width: 100%;">
</p>
- 📺 **Ceefax Ticker** — BBC Ceefax blocky style with the `CeefaxTicker`.

- ⏱️ **SpeedControl Table** — Pick your scroll speed using the `SpeedControl`.

---

## 🧩 **How it works**

- Each carousel or ticker is built with **HTML + CSS** wrapped inside a **DAX measure**.
- The `SpeedControl` table makes the speed dynamic.
- Use the **HTML Content Viewer** visual in Power BI to render the HTML.
- **Fully dynamic**, no JavaScript needed.

---

## ✨ **Original Inspiration**
<p align='center'>
  <img src="img/scrolling-team-cards-html.png" alt="Speed Control Table" style="max-width: 100%;">
</p>
These infinite scrolling ideas were inspired by [Temani Afif’s Infinite Scroll Animation](https://codepen.io/t_afif/pen/jOXRGGx).  
I adapted it into reusable DAX measures and a standalone HTML file — with clear inline comments for learning.

---

## 🗂️ **Included Files**

✅ `/html/ScrollingTeamCard.html` — Self-contained HTML version for quick testing.

✅ `/measures/` — Each DAX measure saved by name:
- `ScrollingTeamCard.txt`
- `FootballProfileStatsCarousel.txt`
- `SalesTeamCarousel.txt`
- `MakeupCountryInflationCard.txt`
- `ProductCarousel.txt`
- `CustomerTestimonialCarousel.txt`
- `KPIHighlightCarousel.txt`
- `CompanyTimelineCarousel.txt`
- `RetroRadioMessageTicker.txt`
- `CeefaxTicker.txt`
- `SpeedControlTable.txt`

✅ **SpeedControl Table** — A simple `DATATABLE` that powers the scroll speed slicer.

---

## 💡 **How to use it**

1. Import the `SpeedControl` table.
2. Add your chosen measure to an **HTML Content Viewer** visual.
3. Connect the speed slicer.
4. Watch your infinite scrolling visuals come to life!

---

## 🎉 **Credits**

- Infinite scroll animation: [Temani Afif on CodePen](https://codepen.io/t_afif/pen/jOXRGGx)
- Tidy Power BI version: *[Your Name]*

---

## 🚀 **Clone, learn, tweak!**

If you find this useful, ⭐ star the repo, clone, tweak, and share it!

