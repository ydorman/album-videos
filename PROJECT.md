# Album videos

Context for every clip session in this project. Keep it short and current.

## Tracks
| # | Title | Clip folder | Status |
|---|---|---|---|
| 03 | Junglelight | clips/03-junglelight | in progress: scene, light, cameras done; costumes first pass (trousers, dresses); choreography next |
| 05 | Mr G's Dance at Seven | clips/05-mr-gs-dance-at-seven | final (reference for look and quality) |
| .. | (8 more tracks to add) | | |

## Shared across all clips
- Visual identity: established by clip 05: dim, backlit, warm-to-violet light following the timbre,
  real-looking people of mixed ages and backgrounds in off-white robes. Not every clip has dancers;
  other clips may use different actors, costumes or backgrounds (the background designer is still to be built).
- Deliverables per clip: full song 16:9 (DistroVid/YouTube) + Instagram snippet 9:16.
- Audio: an MP3 is uploaded for analysis and preview; masters are AIFF 24-bit/48 kHz, used only when rendering on the Mac.

## Decisions and notes
- Clip 05: the downbeat was set by ear on the 1:13 snippet (analysis alone picked a different bar phase); the
  agreed grid is pinned in its track.json. Check the downbeat by ear for every new track.
- Most exact source for the grid: DAW positions (Logic, 25 fps timecode) of the piece start and first downbeat;
  the audio files start at the piece start. Clip 03's grid comes from these.
- Clip 03 (Junglelight): 15/8, eighth = 110 bpm; bar 1 = music start; 2 intro bars + sections A-H of 4 bars
  (pinned in its track.json, to confirm by ear). Story: 3 men, 2 women courting in a jungle clearing; each man is the
  lone one once; ends in a warm circle of all five. Costumes to build: trousers (men), light dresses (women);
  movement language is modern ballet, not the Gurdjieff positions of clip 05.
  Costumes (2026-10-27): men bare-chested in straight relaxed off-white trousers ending below the knee (well above
  the ankle); women in off-white slip dresses with thin straps, ending above the knee. Garments must read as one piece
  (no tight-hips/puffed-legs look, no ridge at the hips). Skirt swing on (look.json `robe.skirt_swing`).
  Colour as storytelling (agreed in an earlier session): each woman has a colour, shown as a subtle tint on her sash;
  her current partner's sash gradually takes on that colour, while the lone man stays untinted. Colours not settled:
  placeholders w1 amber #C98A3E, w2 violet #8C5BA0 (actors.csv sash_color); the pairing in choreography.json
  `partners` is a placeholder (each man lone once: m3 in A-B, m1 in C-D, m2 in E-H) until the choreography is set.
- The intro fades in from darkness; the ending settles into a still bow while the light fades.
