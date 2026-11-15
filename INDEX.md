# Baza skilli — indeks

Skille posegregowane na kategorie. Każdy folder ma `README.md` z listą skilli i opisem, kiedy ich używać.
Jak z tego korzystać: zobacz [PROMPT.md](PROMPT.md).

| # | Kategoria | Kiedy | Skille |
|---|---|---|---|
| 01 | [Blender — rdzeń i pipeline](skills/01-blender-core/README.md) | Zawsze najpierw przy pracy w Blenderze: obsługa MCP, planowanie, kontrola jakości. | 7 |
| 02 | [Modelowanie 3D](skills/02-modelowanie/README.md) | Tworzenie geometrii — wybierz wg typu obiektu. | 13 |
| 03 | [UV, tekstury, materiały](skills/03-uv-tekstury-materialy/README.md) | Po modelowaniu, przed eksportem. | 6 |
| 04 | [Rigging, animacja, symulacje, 2D](skills/04-rigging-animacja-symulacje/README.md) | Ruch, deformacje, fizyka i animacja 2D. | 7 |
| 05 | [Render, kamera, światło, prezentacja](skills/05-render-kamera-swiatlo/README.md) | Finalny obraz, ujęcia produktowe, montaż. | 18 |
| 06 | [Eksport i silniki gier](skills/06-eksport-silniki/README.md) | Ostatni krok przed silnikiem/webem. | 6 |
| 07 | [Style graficzne (art direction)](skills/07-style-graficzne/README.md) | Dobierz 1–2 style jako kierunek wizualny assetu/sceny. | 23 |
| 08 | [Nastrój i horror](skills/08-nastroj-horror/README.md) | Atmosfera — łącz ze stylem z kategorii 07. | 14 |
| 09 | [Światy, epoki, archetypy postaci](skills/09-swiaty-postacie/README.md) | Setting i obsada. | 6 |
| 10 | [Gatunki gier](skills/10-gatunki-gier/README.md) | Język projektowania pod konkretny gatunek. | 13 |
| 11 | [Dokumenty i biuro](skills/11-dokumenty-biuro/README.md) | Gotowe pliki do pobrania/edycji. | 6 |
| 12 | [Design, UX, wizualizacje danych](skills/12-design-ux-wizualizacje/README.md) | Interfejsy, strony, wykresy. | 10 |
| 13 | [Marketing i treści](skills/13-marketing-tresci/README.md) | Bio, posty, kampanie — pilnuj limitów znaków. | 8 |
| 14 | [Produktywność i pamięć](skills/14-produktywnosc-pamiec/README.md) | Zadania, notatki, styl pisania. | 8 |
| 15 | [Programowanie i Claude Code](skills/15-programowanie-claude-code/README.md) | Kod, review, automatyzacje, rozszerzanie samego AI. | 19 |
| 16 | [Przeglądarka, automatyzacja, research](skills/16-przegladarka-research/README.md) | Akcje w przeglądarce i badanie tematu. | 4 |

**Razem: 168 skilli w 16 kategoriach.**

## Luki — brak skilla, AI ma dedukować (kandydaci na nowe skille)

| Obszar | Czego dotyczy |
|---|---|
| Muzyka / Suno / DAW | teksty, struktura w segmentach 5 s, BPM, obsada, prompty do Suno |
| Node.js + Ollama (lokalne agenty) | pipeline Opiekuna: CORE/BRAIN/TASKER/PLANNER/GATE/EXECUTOR, qwen3-coder |
| Native Messaging / rozszerzenia przeglądarki | Opiekun Catcher: most ChatGPT ↔ terminal |
| Android / Gradle / GitHub Actions | Factory-the-app: build APK, keystore, sekrety, artefakty |
| Sprite'y i klatki 2D | PNG bez tła, siatki klatek, ZIP, stałe wymiary 124/256 px |
| Bezpieczne aktualizacje systemu | VM → test → serwer → GitHub, migawki, 3 kopie wstecz |

Gdy luka się powtarza → stwórz skill (`anthropic-skills:skill-creator`) i dopisz go do właściwej kategorii.
