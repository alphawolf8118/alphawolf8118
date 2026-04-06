# Hi, I'm Oliver 👋  
I’m a hands-on builder who works across mechanical design, electronics, software, and AI — and if a project requires a skill I don’t have yet, I learn it.

I specialize in rapid iteration, mechanism design, and turning ideas into physical builds.  
My work blends biological inspiration, CAD modeling, Python tooling, and practical prototyping to create elegant, robust mechanisms.

I sketch my designs, break them into buildable components, and learn whatever skills are required to bring the idea to life — whether that’s CAD, electronics, Python, or new fabrication techniques.


---

## 🛠️ What I Build

- Custom mechanisms and motion systems designed around the problem  
  (I don’t stick to one style — I explore multiple ways to solve a problem and choose the most elegant, buildable approach)

- CAD + physical prototyping in parallel for fast, iterative development

- Electromechanical systems (switches, LEDs, simple circuits, integrated motion)

- Kid-safe, robust home mechanisms and creative engineering tools

- Python-based collection trackers, dashboards, and small utilities

- AI-assisted projects (in progress) to support creative engineering workflows

- Sketch-first design: breaking ideas into buildable components before modeling

- Learning whatever skills the idea requires — CAD, Python, electronics, materials, or new fabrication techniques

- Drawing from real-world biology *as a problem-solving lens* when exploring motion or structure  
  (not biomimicry — just using nature as one of many ways to think through a challenge)

- Clean, minimal, intentional engineering workflows focused on clarity and buildability



---

## 🌸 Featured Projects

### 🌸 Light Up Flower Music Box V2
A complete rebuild of my original light-up flower music box after V1 was broken by my toddler.  
V2 is being redesigned from scratch using sketches, physical intuition, and iterative prototyping — no CAD yet.

The crocus-inspired design came from the mechanical challenge: I wanted a flower that could physically open and close in a clean, radial motion.  
I searched for real flowers that naturally open and close and found that crocuses have:
- a simple, radial bloom motion
- a clean cup-to-star transformation
- a long central pistil that visually resembles an LED cluster

This made the crocus a perfect conceptual guide for designing the bloom mechanism.

V2 is also based on my original circuit, but I’m splitting that circuit into two separate subsystems for better reliability and easier debugging.

Focus areas:
- Rebuilding the flower mechanism with stronger, kid-safe geometry  
- Redesigning the original circuit into two independent modules  
- Exploring multiple mechanical approaches before committing to the final bloom motion  
- Improving the enclosure, stem, and internal structure  
- Keeping the spirit of the original music box while making it more robust and maintainable

**Repo:** [light-up-flower-music-box-v2](https://github.com/alphawolf8118/light-up-flower-music-box-v2)

---

### 📘 Manga Tracker
A Flask + Tailwind + SQLite web app that tracks the collection status of manga series I’m interested in, on hold, actively collecting, or have completed.  
I built this because I wanted a faster, more ergonomic way to track what manga I owned, when the next volume would be released, which Barnes & Noble location had it in stock, and how Amazon’s price compared. I originally managed everything in Google Sheets, but it became too manual and slow as my collection grew.

The main page displays a table of contents with each series grouped by status.  
Navigating into a series shows the volumes I don’t own, their release dates, which Barnes & Noble stores have them in stock, and the current Amazon discount.

Each series page displays a clean table of volumes:
- Purchased volumes are marked in green  
- Unpurchased volumes show which Barnes & Noble locations currently have them in stock  

The project includes a publisher scraper that updates release dates and ISBNs for each volume.  
There was originally a fully automated Barnes & Noble inventory scraper, but after BN increased their automation security, I pivoted to a parser-based approach. The parser extracts store availability from the store list element copied from their website. It’s slightly manual, but far faster and more reliable than entering each store location individually.

**Repo:** [manga-tracker](https://github.com/alphawolf8118/manga-tracker)


---

### 🃏 TCG Tracker
A Django + Tailwind + SQLite web app that tracks the collection status of Magic: The Gathering and Pokémon cards.  
I built this because I needed a digital database to track my trading cards, complete sets, and quickly see which Pokémon I still needed. I didn’t like the existing tools, so I made my own.

I chose Django for future-proofing because it supports multiple users, allowing each person in my family to manage their own collections independently.

The MTG section pulls the latest sets from Scryfall using an ingestion script.  
You can group sets into binders, and each set displays a collection progress bar.  
Inside a set, each card shows its image, name, and collector number, and you can mark whether you own the non-foil, foil, or both.  
There’s also an Export Missing Cards button that generates a CSV so I can upload it to Google Sheets and use it when hunting for cards at local MTG stores.

The Pokémon section is organized like a Pokédex.  
My goal is to collect one of each Pokémon.  
Collected Pokémon are marked, and the progress bar updates automatically.  
There’s also a search feature so you can jump directly to a Pokémon by number instead of paging through the entire dex.  
An Export Missing Pokémon button provides the same CSV workflow as the MTG section.

I currently support MTG and Pokémon, with plans to add Lorcana and Riftbound as additional TCGs.

**Repo:** [tcg-tracker](https://github.com/alphawolf8118/tcg-tracker)

---

## 📚 Additional Python Projects

### 🎎 Pop Mart Tracker
A lightweight Flask app with CRUD, image uploads, and Alembic migrations.  
Built to quickly track Pop Mart figures in a set with a simple, clean UI.  
**Repo:** [pop-mart-tracker](https://github.com/alphawolf8118/pop-mart-tracker)

### 🎬 Movie Tracker
A simple tool to track the collection status of films in a movie collection like the MCU or Harry Potter.  
Lightweight, minimal, and built to be extended later.  
**Repo:** [movie-collection-tracker](https://github.com/alphawolf8118/movie-collection-tracker)

---

## 📸 Visual Highlights
Early sketches from the Light Up Flower Music Box V2 design process.  
These show my initial exploration of petal geometry, hinge placement, and crocus‑inspired bloom motion.

![Sketch 1](sketches/Light-Up-Flower-Sketch-1.jpg)
![Sketch 2](sketches/Light-Up-Flower-Sketch-2.jpg)

*(More visuals coming as I begin prototyping and part selection.)*

---

## 🚀 What I'm Working On Now
- Finalizing Flower V2 lighting + cam switch integration  
- Refining crocus-inspired hinge + petal geometry  
- Expanding my mechanism portfolio with new crank/cam systems  
- Prototyping a new electromechanical device (V0 parts in progress)  
- Building personal AI tooling and experimenting with multi-agent workflows  

---

## 🎯 What I'm Aiming For
- Hands-on engineering roles where I can design, prototype, and build across mechanical, electrical, and software domains
- Mechanism design and creative hardware development  
- Building physical products that combine mechanical design, electronics, and software  
- Prototyping electromechanical tools and experimental devices  
- Developing AI-assisted engineering workflows and internal automation tools   

---

## 📫 Contact
- **LinkedIn:** www.linkedin.com/in/oliver-yang-30169636
- **Email:** oliver.yang2026@gmail.com

