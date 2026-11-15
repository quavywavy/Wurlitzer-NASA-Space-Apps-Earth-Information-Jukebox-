
# 🌍🎵 EcoSonic

> **“Exploring Earth’s Sounds to Protect Tomorrow’s Sights”**
> By **Team Wurlitzer** for the **NASA Space Apps Challenge**

**Live site:** https://quavywavy.github.io/Wurlitzer-NASA-Space-Apps-Earth-Information-Jukebox-/

**Team Members:** Tusankine Amy Mumba · Timothy Namakobo · Benjamin Mwanza · Ngiyabonga Njobvu · Wanzya Nauluta

---

## 📝 About

NASA’s Earth data is mostly visual, which shuts out blind and low-vision users and anyone who struggles with colour-coded maps. **EcoSonic** lets people **see, hear and talk to** NASA vegetation data. Pick any place on a 3D globe and EcoSonic reads its **NDVI** (Normalized Difference Vegetation Index, a satellite measure of how green and healthy vegetation is), shows the satellite imagery, and turns the reading into music, in *16 languages* with the option of **voice control**.

It is built for schools, students, decision makers and curious explorers, so no one is left behind in understanding our changing world.

---

## ✨ Features

- 🌐 **3D globe:** click or name any place on Earth
- 🛰️ **NASA imagery:** true colour, NDVI and a 12-month animation
- 🎵 **Sonification:** greener places sound higher, fuller and livelier
- 🗣️ **Voice guide:** hands-free navigation with spoken replies and live captions
- 🌍 **16 languages:** including Cinyanja, Ichibemba and Silozi
- 👧🧑👩 **Age modes:** Children (0–12), Teens (13–17), Adults (18+)
- 📚 **Learn tab:** what NDVI is, why it matters, and explainer videos

---

## ⚙️ How It Works

1. **Choose a place** on the globe or by voice (e.g. Lusaka, the Amazon, the Congo Basin).
2. **Fetch imagery** from NASA GIBS: the **MODIS Terra 8-day NDVI** layer plus daily true colour.
3. **Estimate NDVI** by matching image colours to the NDVI scale over a 5 × 5 pixel area.
   `NDVI = (NIR − Red) ÷ (NIR + Red)`
4. **Play the sound:** NDVI controls pitch (pentatonic scale), number of notes (3 to 8), tempo and tone. Water, ice and cloud play a soft ocean wash.
5. **Explain:** the voice guide describes the place and its reading in the chosen language.

---

## 🛠️ Built With

HTML · CSS · JavaScript · **globe.gl** and **three.js** (3D globe) · **Web Speech API** (voice) · **Web Audio API** (sound) · **NASA GIBS** and **Worldview** (data)

Everything is one `index.html` file: no installation needed.

---

## 🚀 How to Use

Open the live site in **Chrome** or **Edge**, press **Begin your journey**, choose an age group, and open the **NDVI Jukebox**. Press **V** and say **“help”** for voice control. Try *“Take me to Lusaka”* or *“What am I hearing?”*

---

## ♿ Impact

- Gives **low-vision users, kids, students, and the elderly** access to vegetation data through sound and voice.
- Brings NASA science to **local-language speakers**.
- Supports **UN SDG 4 (Quality Education)** and **SDG 13 (Climate Action)**.
- Useful for tracking **drought, crop health and deforestation** with free NASA data.

---

## ⚠️ Limitations and Future Work

- Covers **vegetation (NDVI) only**. Next: temperature, rainfall and **NASA GEDI canopy height** for carbon estimates.
- Readings cover a large area (about 0.9°), so they show **regional patterns**, not single fields.
- **Zambian-language** text needs native-speaker review, and those languages are spoken with a Swahili voice.
- Voice recognition works in Chrome and Edge only (a typed box is the fallback). An internet connection is required.
- Next steps: testing with visually impaired users, and an offline mode for schools.

---

## 📚 References

- NASA Earth Observatory (2000). *Measuring Vegetation (NDVI & EVI).* https://science.nasa.gov/earth/earth-observatory/measuring-vegetation-ndvi-evi/
- USGS (2024). *Landsat Normalized Difference Vegetation Index.* https://www.usgs.gov/landsat-missions/landsat-normalized-difference-vegetation-index
- Elkins, K. (2021). *GEDI Forest Height.* NASA SVS. https://svs.gsfc.nasa.gov/4950/
- Lang, N. et al. (2023). A high-resolution canopy height model of the Earth. *Nature Ecology & Evolution.* https://doi.org/10.1038/s41559-023-02206-6
- NASA GIBS: https://nasa-gibs.github.io/gibs-api-docs/

<p align="center"><b>EcoSonic</b> · Team Wurlitzer 🌍🎶</p>
