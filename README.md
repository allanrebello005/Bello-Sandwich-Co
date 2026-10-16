# Bello Sandwich Co.

Open `index.html` directly in a browser. No build or installation is needed.

## Editing

- CSS tokens at the top: `--red`, `--yellow`, `--black`, `--cream`, `--display`, `--body`, `--max` (content width), `--speed` (transitions).
- `PRICES` near the start of the script: all eight sandwich prices and the per-extra price.
- `INSTAGRAM_HANDLE`: replace `[INSTAGRAM_HANDLE]` with your account name. All Instagram links update together.
- The comment `WAITLIST SUBMIT URL GOES HERE` marks the form integration point. Currently it validates only, and sends or stores nothing.

## Photos

Put your photographs in the adjacent `images` directory:

hero-burger.png, chicken-cafreal.png, grilled-chicken.png, chicken-cutlet.png, roast-beef.png, beef-cutlet.png, carne-de-porco.png, chicken-supreme-slider.png, beef-supreme-slider.png, sauce-kokum-mayo.png (optional).

Missing photos show red Bello placeholders. Below-the-fold photos load lazily. Google Fonts requires a connection; fallback fonts work offline.

## Included sections

- [x] Sticky navigation, mobile menu, Instagram link and order counter
- [x] Split hero; image above text on mobile
- [x] Eight-item menu with filters, prices and Build this actions
- [x] Six-protein builder, five sauces, multi-select extras and animated price
- [x] Five expandable sauce cards
- [x] Email validation, preview confirmation and Instagram call to action
- [x] Our Story
- [x] Footer

Slider Build this actions choose Grilled Chicken or Roast Beef respectively, keeping the builder to six protein options. Orders are held in memory and disappear on refresh. The form does not create real subscriptions.

## Verification

JavaScript syntax checked. The file is approximately 29 KB, excluding images and external fonts. Responsive CSS covers 390px and 1280px, but browser-based visual and interaction checks at those widths remain unverified. The local preview connection was blocked by environment socket permissions.


Your supplied PNG photos are connected in `images`, including all five sauce bottles. Original files remain in `Bello sandwich images`. The beef supreme slider photo is also used for the hero.


## Current brand logo assets

The header uses `images/bello-wordmark-color.svg` at 160–180px with clear space. The footer uses `images/bello-primary-white.svg` at 280px on black. Both preserve native proportions and transparency without cropping, recolouring or stretching. Browser and Apple touch icons come from `Bello-Logo-Package/icons`. The original logo package is preserved.

