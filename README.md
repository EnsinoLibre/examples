<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/EnsinoLibre/assets/main/wordmark-primary-dark.svg">
  <img src="https://raw.githubusercontent.com/EnsinoLibre/assets/main/wordmark-primary-light.svg" alt="EnsinoLibre" width="360">
</picture>

# examples — community worksheets

</div>

---

Ready-to-use EnsinoLibre worksheets to fork, adapt and learn from. Each is a single `.worksheet.json` file in the EnsinoLibre format — paste it into the [builder](https://github.com/EnsinoLibre/core) to use it interactively, print it, or export the analog Markdown version.

All worksheets here are shared under **[CC BY-SA 4.0](LICENSE)** — use them, remix them, keep credit, and share your changes alike.

## Contents

| Subject | Worksheet | Level |
|---------|-----------|-------|
| Science | [Solar System](science/solar-system.worksheet.json) | Year 6 |
| Mathematics | [Introducing Fractions](mathematics/fractions-intro.worksheet.json) | Year 4 |
| Languages | [Daily Routines](languages/daily-routines-a1.worksheet.json) | EFL A1 |

Every worksheet validates against the [`blocks`](https://github.com/EnsinoLibre/blocks) schema.

## How to use one

1. Open a worksheet file and copy its contents.
2. Go to the [builder](https://github.com/EnsinoLibre/core), scroll to **Render your worksheet**, paste, and click **Render**.
3. Use it on screen, **Print / save as PDF**, or **Download analog version** for a paper handout with an answer key.

## Contributing a worksheet

Add a `.worksheet.json` file under the right subject folder (create one if needed) and open a PR. Keep it self-contained (no external images or audio — spoken text goes in `transcript`/`text` fields), make sure answers are correct, and validate it in the builder first. See the [docs](https://github.com/EnsinoLibre/docs) for the format.
