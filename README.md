# Box Score Sudoku

Rebuild a 1920 World Series game from its newspaper box score.

**Play:** https://so-called-bourbaki.github.io/box-score-sudoku/

The givens are everything printed in the box score from the October 11, 1920 *Evening Star*
(Cleveland 8, Brooklyn 1, World Series Game 5). The rules:

1. Every side proves: at-bats + walks + sacrifices = runs + runners left on base + the other side's putouts.
2. The batting order is a clock. From a team's trips to the plate you know who came up, and how often.
3. Every half-inning ends on its third out, and at most three men can be left on base.
4. The line score says which innings had runs.

Most of the game is forced by the page. The puzzle is finding the cells that aren't.

`index.html` is the whole game; the box score image is embedded. It saves progress in your browser's local storage. No ads, no tracking, no account.

Scan: Evening Star (Washington, D.C.), October 11, 1920, p. 21. Library of Congress, Chronicling America. Public domain.
Play-by-play used for the answer key: Retrosheet (www.retrosheet.org), used under its notice.

Part of [So-Called Bourbaki](https://socalledbourbaki.substack.com).
