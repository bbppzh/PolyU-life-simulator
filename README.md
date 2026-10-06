# PolyU Life Simulator — All Versions

Five editions in one repository. Each folder opens directly into its game; the homepage displays the collection. No ChatGPT account, login or AI API is required.

**Current terms: personal play only; academic and commercial reuse require prior written permission.** See [LICENSE](LICENSE). This is a custom restricted license, not an open-source license. Earlier MIT releases and material retain their MIT permissions; see [LEGACY-MIT-NOTICE.txt](LEGACY-MIT-NOTICE.txt). Third-party licenses and statutory exceptions remain intact.

[Play the collection](https://bbppzh.github.io/PolyU-life-simulator/)

| Version | Game | Interface and features | Play |
| --- | --- | --- | --- |
| V1 | 14-week semester, talents, visible stats, six endings | Original light interface | [V1](https://bbppzh.github.io/PolyU-life-simulator/v1/) |
| V2 | Original semester gameplay | Pixel campus, retro interface | [V2](https://bbppzh.github.io/PolyU-life-simulator/v2/) |
| V3 | Four years, six major directions, 32 decisions, four hidden scores, eight endings | Text-driven interface and major-specific scenarios | [V3](https://bbppzh.github.io/PolyU-life-simulator/v3/) |
| V3.1 | Four years, two talents, 16 attribute points, live status, semester GPA and CGPA | Pixel interface, original campus illustration, layered electronic music and Music ON/OFF button | [V3.1](https://bbppzh.github.io/PolyU-life-simulator/v3.1/) |
| V3.2 | All V3.1 features; recurring characters and relationship memory; 32 main moments + 3 follow-ups; 8 optional seeded events from a pool of 16 (43 choices when enabled) | Red-brick pixel UI, live music spectrum, separate music/effects volumes, keyboard shortcuts, graduation timeline, same-seed replay and feedback questionnaire | [V3.2](https://bbppzh.github.io/PolyU-life-simulator/v3.2/) |

## Download every version

Click **Code → Download ZIP** in this repository. It contains all five version folders. Each folder contains a self-contained `PolyU-Life-Simulator.html` for offline desktop play. Open that file in a browser with JavaScript enabled. On iPhone, use Safari to open the public website; the Files preview may not execute the game.

## V3.1 music

The header Music ON/OFF button controls “After Class — Arcade Mix”, an original 32-bar electronic chiptune arrangement at 112 BPM synthesised locally in the browser. Music starts only after a click. Turning it off cancels scheduled notes; switching away from the page pauses music. Tap again to resume. Its intro, groove, breakdown and reprise combine melody, arpeggios, pads, counter melody, bass and drums. No audio files, streaming services or external APIs are needed. The pixel campus SVG is original; the bundled Pixelify Sans font uses the SIL Open Font License.

## V3.1 live status and grades

Choose two talents, then distribute 16 points among Focus, Social, Discipline and Luck (0–8 per attribute). Your allocation changes gameplay effects and uncertain outcomes. Live status shows Semester GPA, CGPA, Sanity, Social Value and Resume Strength.

Current-semester GPA is an estimate updated by choices. Four decisions complete a semester; its final GPA is recorded and CGPA becomes the average of completed semester GPAs. Each term has equal weight in this game. The results table keeps all eight semesters and the graduation story uses final CGPA. V3 retains its original hidden-score mechanics.

## V3.2 story edition

V3.2 retains the V3.1 interface, music, six majors, eight talents, attribute allocation, live status, transcript, journal and eight ending categories. Jade (roommate), Ken (teammate) and Dr Leung (supervisor) recur with their own priorities and relationship memories. The missing-teammate, hall-conflict and capstone moments each lead to one of three follow-up scenes, then rejoin the semester. Each playthrough has 32 main moments and three follow-up choices. Optional campus surprises add eight unique events from a pool of 16, one per semester, for 43 choices in total. A numeric or text seed lets players recreate the same events and outcomes with the same character build and choices.

All 24 major scenarios have individually written consequences. The latest teamwork agreement changes later expectations; internship rejection produces an explicit alternative-placement plan; exchange/research/local choices return in later projects and personal ending paragraphs. Final semester GPA and CGPA are fixed after the last exams, before next-step and farewell choices. See [V3.2 story map](v3.2/STORY-MAP.md). V3.1 keeps its original stories and grade timing.

## Structure

- `index.html`: the collection homepage.
- `v1/`, `v2/`, `v3/`, `v3.1/`, `v3.2/`: playable versions and offline HTML downloads.
- `PolyU-Life-Simulator.html`: the previously shared root offline URL, preserved as V2.
- `LICENSE`: custom Personal-Play License; academic and commercial reuse require written permission.
- `LEGACY-MIT-NOTICE.txt`: preserved permissions for earlier MIT versions/materials.
- `FONT-LICENSE.txt`: Pixelify Sans license; also included in pixel editions.

Game code and styling are included in the HTML for personal play and private source inspection under the applicable license. Progress stays in the current page session; refreshing, closing or changing versions starts a new game. Character names are not sent to a server.

Existing standalone V1, V2 and V3 websites remain available. All five playable editions are now also collected here. This is an unofficial fictional student game; events, grades and endings do not represent real university decisions.

## License

**Current terms: personal play only; academic and commercial reuse require prior written permission.** See [LICENSE](LICENSE). This is a custom restricted license, not an open-source license. Earlier MIT releases and material retain their MIT permissions; see [LEGACY-MIT-NOTICE.txt](LEGACY-MIT-NOTICE.txt). Third-party licenses and statutory exceptions remain intact. V2's fictional campus panorama was AI-generated. Pixelify Sans is bundled under SIL OFL, with notices in the HTML and font license files.
