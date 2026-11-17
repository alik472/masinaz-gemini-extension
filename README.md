# Masin.az for Gemini CLI

Search the cars and number plates for sale on [masin.az](https://www.masin.az), the Azerbaijani car marketplace, from Gemini CLI. No account or API key is needed.

## Install

```bash
gemini extensions install https://github.com/alik472/masinaz-gemini-extension
```

That is all: there is no account, sign-in or API key.

## What you can ask

- Find Mercedes-Benz cars in Baku under 30,000 AZN, cheapest first.
- Show me Hyundai Elantra listings under 25,000 AZN.
- Find number plates with the digits 111.
- Which car makes have the most listings on masin.az?

## Tools

| Tool | What it does |
| --- | --- |
| `search_cars` | Cars for sale filtered by make, model, year, price, city, fuel, gearbox, drive, condition, colour, mileage or keyword. |
| `search_plates` | Azerbaijani registration plates (like 90-SK-600) by whole plate, region code, letters or digits. |
| `get_listing` | Full details of one car or plate listing: price, description, attributes, city, photos and link. |
| `list_makes_and_models` | Makes, or one make's models, spelled the way masin.az lists them, with listing counts. |
| `list_categories` | What masin.az lists, and the cities and districts that have listings. |
| `list_dealers` | Car dealers (salons) with their location, number of listings and page on masin.az. |

## Good to know

- Every tool only reads public listings. Nothing can be posted, bought or paid for, and no seller is contacted.
- Seller phone numbers and private names are never returned. To contact a seller, open the listing link on masin.az.
- Prices are shown as published, usually in Azerbaijani manat (AZN). Seller descriptions are in Azerbaijani.

## Other MCP clients

The extension only points Gemini CLI at Masin.az's hosted MCP server (streamable HTTP):

```
https://www.masin.az/mcp
```

Any MCP client that supports remote servers can use the same address. It needs no authentication.

## Links

[Website](https://www.masin.az) · [About the AI tools](https://www.masin.az/ai-assistants) · [Privacy](https://www.masin.az/ai-assistants/privacy) · [Terms](https://www.masin.az/ai-assistants/terms)

## License

The files in this repository are released under the MIT License. The Masin.az service itself is covered by its terms.
