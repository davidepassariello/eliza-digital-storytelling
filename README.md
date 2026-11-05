# I silenzi di ELIZA - Interactive Digital Storytelling

**HTML · CSS · JavaScript · Digital Humanities · Human–Computer Interaction**

An immersive, Italian-language, vertically scrolling digital story about **ELIZA**, the 1966 conversational program created by Joseph Weizenbaum, and the origins of the *ELIZA effect*: the tendency to attribute understanding or empathy to a computer's responses.

## Live Demo

🌐 [Explore the interactive ELIZA storytelling website](https://davidepassariello.github.io/eliza-digital-storytelling/)

An immersive, scroll-based narrative exploring the origins of the ELIZA effect and the history of human-computer interaction.

## About the project

Developed as an **academic group project** for the *Digital Storytelling Laboratory* by **Davide Passariello and Silvana Pecoraro**. The narrative adopts the point of view of ELIZA's code, interweaving historical context, excerpts from early human–machine conversations and a critical discussion of emotional projection onto machines.

The story is a historical and interpretive experience: **it is not an LLM or a recreation of a real AI therapist**.

## Features

- Single-page vertical scrolling narrative with section transitions and animations
- Responsive layout and archival-inspired visual design
- Interactive elements and a simulated historical ELIZA dialogue
- Accessibility-oriented display controls and optional synthesized interface sounds
- Bibliography and links to museum collection records

## Run locally

1. Download the repository (Code → Download ZIP), then extract it.
2. Open `index.html` in a modern browser.
3. Scroll to explore the story. No installation, server or database is needed.

Alternatively, serve the folder with `python -m http.server 8000` and open `http://localhost:8000`.

## Publication and sources

This portfolio adaptation uses **original graphic placeholders** instead of third-party museum photographs. Each placeholder identifies the object and the corresponding institution; source links remain in the webpage's bibliography. The original academic bundle included an article PDF and a separate MP3 track. Copies of both are kept in `reference-materials/` for reference. **Citation and attribution do not automatically grant permission to redistribute or host these copyrighted materials publicly.** Check the applicable rights or replace the PDF with a link to the publisher and the MP3 with a licensed alternative before making the repository public or enabling GitHub Pages.

The website's optional synthesized interface tones are generated with the browser's Web Audio API. The bundled MP3 is **not connected to playback** in `index.html`.

**Selected references**

- Weizenbaum, J. (1966). *ELIZA — A Computer Program for the Study of Natural Language Communication Between Man and Machine*. Communications of the ACM, 9(1), 36–45.
- Weizenbaum, J. (1976). *Computer Power and Human Reason*. W. H. Freeman.
- MIT Museum Collection and Computer History Museum object records (linked in the webpage).

## Project status

Educational prototype. The website is static and can be hosted with GitHub Pages. This portfolio adaptation is not endorsed by MIT or the institutions whose collections are referenced. No claim is made that its visual narrative reproduces ELIZA's original program exactly.

## Credits

**Academic project:** all code authored by Davide Passariello. The underlying site comes from the group's submitted materials. This repository packages and documents a public-safe portfolio adaptation.
