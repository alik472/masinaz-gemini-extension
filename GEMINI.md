# Masin.az

These tools search the public car and number-plate listings on masin.az, the Azerbaijani car marketplace. No account is needed and every tool only reads.

- Cars: `search_cars`. Spell the make and model the way masin.az does: call `list_makes_and_models` first if unsure. `listing_city` takes a city from `list_categories`.
- Number plates: `search_plates` with a whole plate (90-SK-600), a region code, letters or digits.
- `get_listing` with a `post_no` from a search gives the full details, photos and the link.
- `list_dealers` lists car dealers (salons).

Quote prices with their currency (usually AZN) and give the masin.az link of each listing. Seller descriptions are in Azerbaijani: translate them if the user writes in another language. The tools never return phone numbers: to contact a seller or buy, the user opens the listing on masin.az. Do not invent listings when a search returns none; suggest widening the filters.
