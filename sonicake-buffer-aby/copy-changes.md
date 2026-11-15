# Copy changes: Sonicake Buffer ABY (QSS-23)

## Sources

- `QSS-23_Manual.pdf`: the single-page card, byte-identical to
  https://cdn.shopify.com/s/files/1/0100/1950/4185/files/QSS-23_Manual.pdf
  (linked from https://www.sonicake.com/products/buffer-aby). No text layer:
  the whole card is one flattened image, so the copy was read off the
  300-dpi render and checked against an OCR pass.
- https://www.sonicake.com/products/buffer-aby: feature bullets, input and
  output impedance, dimensions with D/W the right way round, product photos
  (`pedal-top.jpg` = QSS-23-1, `pedal-on-board.jpg` = QSS-23-7). The "Built-in
  High-Quality Buffer Circuitry" image says "When BUFFER is turned off, the Y
  interface can be used for output".
- https://www.amazon.com/dp/B0DB7T5JMK, product description: "Can Be Used
  Without Power Supply. Turn off the BUFFER switch and it can be used even
  without power. At this time, it is true bypass."
- Owner reports: sonicake.com reviews (2), Amazon Japan, Amazon Italy.

## Departures from the print

| Section | Printed | Page |
|---|---|---|
| intro | `instruments - You decide!` | `instruments – You decide!` (dash) |
| intro | (not on the card) | feature bullets from sonicake.com; "Working with" -> "Works with", "You Can choose True Bypass keeps a clean Signal Path or Buffer Circuitry to improve" -> "You can choose true bypass to keep a clean signal path, or buffer circuitry to improve", caps normalised |
| connections | callouts around the drawing | a legend beside the maker's top-view photo; each callout under the part it points at (DC 9V, A and B jacks, Y jack, A/B – AB switch, BUFFER switch, Footswitch and LED) |
| connections | `Switch from two different modes:` | `Switch between two different modes:` |
| connections | `toggle between A (A↔Y)/B (B↔Y) channels` | `toggle between A (A↔Y) / B (B↔Y) channels;` |
| connections | `BUFFER switch, you can choose whether to turn on the Buffer circuit` | term `BUFFER switch`, text `You can choose whether to turn on the Buffer circuit …` |
| modes | (not on the card) | routing table compiled from the card's callouts and the sonicake.com image text |
| buffer-and-power | (not on the card) | Amazon description quoted; impedance sentence; the card's Y-output rule repeated with the sonicake.com image text |
| specifications | `Dimensions: 93.5mm (W) x 42mm (D) x 52mm (H)` | `93.5mm (D) x 42mm (W) x 52mm (H)`, as on sonicake.com; QSS-23-5 shows 93.5 mm is the length |
| specifications | (not on the card) | input impedance 1MΩ, output impedance 1kΩ from sonicake.com |
| owner-reports | (not on the card) | buyer reviews, paraphrased in English, each linked to its store |

## Conflicts left open

- Current draw: card and sonicake.com print 80mA; RockBoard PedalPedia lists
  10mA. The page keeps 80mA.
- Impedance: sonicake.com does not say which BUFFER position the 1MΩ / 1kΩ
  figures are for; a sonicake.com reviewer raises the same gap.
