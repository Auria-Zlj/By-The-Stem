# By the Stem

**A concept for a flower shop that sells by the stem, where the homepage is the wrapping bench.**

You pick single stems off a hand-drawn shelf, arrange them on a sheet of wrapping paper, wrap them into a bouquet, and leave with a card of the bunch you made. The shop's florist, a small lemon-coloured bird, keeps you company the whole way.

![Arranging a bunch on the bench](docs/bench-arranging.jpg)

> By the Stem is a design concept. There's no shop yet, and nothing is ever charged.

---

## The idea

Most flower shops online sell finished bouquets from a grid of photos. In a real shop it works the other way: you point at a few stems, the florist gathers them in their hand, and the bunch takes shape in front of you.

By the Stem brings that moment online. There is no product page to browse; the first thing you see is an empty sheet of paper on the counter and a shelf of today's stems beside it.

## How it works

1. **Pick stems.** Drag a stem from the shelf onto the paper, or tap it to drop it in. There are 20 flowers over three shelf pages. A few come in two colours, and a few are running low ("4 left").
2. **Arrange.** Drag a flower to move it. Drag it lower to cut its stem shorter. Tap it to bring it to the front, or drag it off the paper to take it out. The stems always gather at one tie point, so the bunch stays a bunch.
3. **Choose a paper.** There are five hand-drawn papers: kraft, newsprint, gingham, dots and stripes.
4. **Wrap.** The paper folds around the stems, the twine ties itself, and a tag drops down.
5. **Write on the tag.** Tap the tag to write a short note, like *for Mom, with love*. The note appears on your card.
6. **Buy, and the shop isn't open yet.** "Buy this bunch" leads to an *Opening soon* sign and a note from the florist. Instead of a receipt you get a card of your bunch, in one of three styles, which you can save.

![The Opening soon page with the card](docs/opening-soon.jpg)

## Design decisions

- **The homepage is the bench.** The interaction is the product, so it starts immediately, with an empty paper, a dashed flower and one line of instruction.
- **A florist, not a tutorial.** Hidden gestures such as cutting a stem, bringing a flower forward or taking it out are taught by the bird the first time they become useful, one tip at a time. After that it comments on your bunch now and then ("Tall spires with round blooms: a good shape"). It sits on the paper's corner rather than in the middle of the screen, so it never gets in the way. It flies off while you wrap and lands on the *Opening soon* sign at the end.
- **An honest ending that stays in the story.** A concept can't take orders, but breaking the fiction with "this is a demo" spoils it. The shop simply hasn't opened yet, and a small line at the foot of the page states plainly that it's a concept.
- **Something to keep.** The note on the tag and the card turn a pretend purchase into something personal you might actually share.
- **One drawing language.** Every flower, paper, card and the bird is drawn the same way: a fine olive ink line with the colour printed slightly off the line, like a riso print. Hand-lettered type (Nanum Pen Script and Patrick Hand) and a calm palette keep the stems as the loudest thing on the page.
- **Grouping and breathing room.** The shelf and its pager form one group, and the paper with its paper choice, price and button form another. The bench is optically centred and scales with the window height, so it fits a laptop screen and doesn't balloon on a big monitor.

## Running it

It's a single self-contained HTML file with no build step or dependencies; fonts load from Google Fonts. Open `index.html` in a browser, or turn on GitHub Pages for this repository.

Designed for desktop and laptop screens.

## What's in the repo

| Path | What it is |
|---|---|
| `index.html` | The finished site |
| `docs/` | Screenshots used in this README |
| `explorations/` | Working pages from the design process: style samples, layout studies, flower, paper, card, pager, shopkeeper and speech options, and the first versions of the bench |

## Credits

Concept and design by Auria Zhang. All flowers, papers, cards and the florist bird are drawn in code as SVG and canvas.
