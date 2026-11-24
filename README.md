# Math Quiz 3.0

An iteration of the two-player multiplication quiz with answer calculation.

**Repository created:** 2021-09-05  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2021-09-05

## Features and implementation

- Store player names.
- Display scores and turns.
- Parse numbers and compute their product.
- Dynamically render answer controls.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery.

## Project structure

| File | Purpose |
| --- | --- |
| [`gamepage.html`](gamepage.html) | Quiz game interface |
| [`gme.js`](gme.js) | Question and game logic |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `gme.js`: `send()`.
- `main.js`: `addUser()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/Math_Quiz-3.0.git
cd Math_Quiz-3.0
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Enter player names and generate a multiplication question.

## Current status and limitations

The Check handler is not implemented in this snapshot.

## Related project snapshots

Other repositories in this project family:
- [Math_Quiz_1.0](https://github.com/Avenger-Sonic123/Math_Quiz_1.0) — repository created 2021-08-23
- [Math_Quiz-2.0](https://github.com/Avenger-Sonic123/Math_Quiz-2.0) — repository created 2021-09-05
- [Math_Quiz_Completed](https://github.com/Avenger-Sonic123/Math_Quiz_Completed) — repository created 2021-09-19

---

Source reference: [`d2971e02`](https://github.com/Avenger-Sonic123/Math_Quiz-3.0/tree/d2971e02488f5b6f88869961af8dbebdc7112e47) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
