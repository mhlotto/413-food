# Data schema and style

- Keep entries alphabetized by `name`.
- Strings in quotes only when they contain punctuation; phone numbers as `413-555-0100`.
- `price`: `$`, `$$`, or `$$$` (rough guide, not exact).
- `hours`: use 24h ranges like `11:00-21:00`; use `closed` if not open that day.
- `ordering`: any of `dine-in`, `takeout`, `delivery`.
- `dietary`: booleans; default to `false` if unknown.
- `highlight_items`: keep to 1-3 items with short notes.
- `sources`: cite how you know (visit date, menu URL, Instagram update).

## Field reference
- `name`: Restaurant name.
- `neighborhood`: e.g., Downtown Amherst, North Amherst, Hadley.
- `address`: Street, city, state.
- `coordinates`: Optional, `lat` and `lng` decimals.
- `phone`, `website`: Contact info.
- `cuisine`: Short description (e.g., "Middle Eastern", "Thai", "Coffee").
- `price`: `$`/`$$`/`$$$`.
- `ordering`: List of service modes.
- `dietary`: `vegetarian_friendly`, `vegan_options`, `gluten_free_friendly`.
- `hours`: Map of day -> time window string.
- `highlight_items`: List of signature dishes with `item` and `note`.
- `notes`: Freeform quick facts (parking, cash-only, wait times, seasonal).
- `comments`: Optional list of short freeform notes (e.g., user observations, seasonal specials).
- `last_verified`: Date you confirmed the info.
- `sources`: List of `{ type, detail }` entries.
