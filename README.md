# Sleight of Mind

An AI capability-elicitation eval, starting with chess. Can a language model play at a rating you choose, or does it give itself away?

Live site: https://yashrao10.github.io/sleight-of-mind/

All 117 positions are scored and the figures on the site are final for this run. It is one model on 117 positions, so read it as a first result, not a verdict on the method. The evaluation code and data live in [chess-sandbagging-eval](https://github.com/YashRao10/chess-sandbagging-eval). The site is a single static page (`index.html`). The Play board uses chess.js from a public CDN, and its opponent is a second Stockfish held back by Skill Level and depth to match the dial, a rough stand-in for the model.
