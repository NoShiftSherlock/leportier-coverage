# Le Portier coverage page

Private sales demo by AccelPay that uses Le Portier's brand name. Not affiliated with or
endorsed by Le Portier. Keep the link unlisted; share it 1:1 only.

Live: https://noshiftsherlock.github.io/leportier-coverage/

Built with the `alcohol-coverage` skill on 2026-10-24:
- Retailer network: `network_coverage.py` (ReserveBar/AccelPay retailer catalog, active
  listings matching LE PORTIER / Shay VSOP by brand or name, Gopuff excluded): 121 of 361
  network retailers. Cross-checked with `retailer_inventory_check.py` (Liquor Barn sheet: 8 in
  stock; Main Street sheet: listed, 0 stock, already counted as no listing).
- Gopuff: BigQuery snapshot (stale, 2026-06-17) showed 0. A live brand-facet check of all 173
  spirits-licensed (BWS) Gopuff locations found "Le Portier Shay" at 7 (Chandler, Glendale,
  Goodyear, Peoria, Phoenix, Scottsdale, Tucson); 164 of 173 passed the cognac control.
- Map tiles: Esri Canvas (CARTO tiles now watermark without a key).

Re-running `cpg-coverage-cli map "Le Portier"` drops the network layer and the copy edits.
