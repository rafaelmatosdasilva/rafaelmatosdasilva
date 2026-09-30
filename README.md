# Design systems that code and AI can trust

Freelance Design System Architect and Brand Identity Lead, based in Lisbon.

I build tooling that keeps a design system true between Figma and code: the real tokens, components, props and states, named exactly as the system names them, so people and AI agents build with the system instead of guessing it.

---

## Building
[rms-design-system-engine](https://github.com/rafaelmatosdasilva/rms-figma-code-parity) The engine of a design system, as a Claude Code skill. It runs 25 checks of the code against its Figma file (tokens in every mode, structure, states, variants, props, markup, icons, motion, shadows, rendering in a real browser and accessibility) and gives the file and line to change, with a ready patch. It answers which components, props and tokens exist, named exactly as they are, and writes them out so AI tools build with the real system. It checks every UI an AI generates and each edit as it is made, Tailwind classes included, and reviews the Figma file and the agents' instructions too. The engine makes the decisions, so it works the same on a small model as on a large one.

[rms-ds-figma-plugins](https://github.com/rafaelmatosdasilva/rms-ds-figma-plugins) Open-source Figma plugins for design system teams: Impact Atlas traces token dependencies, Tokens to Ink extends colour tokens into print, Font Scaling Lab stress tests layouts under text scaling.

---

[rafaelmatosdasilva.com](https://www.rafaelmatosdasilva.com) · [LinkedIn](https://www.linkedin.com/in/rafaelmatosdasilva)
