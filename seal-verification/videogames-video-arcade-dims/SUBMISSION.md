# Video Games — 1977 Sears Tele-Games Video Arcade console size

## Prompt
In the calendar year Jimmy Carter was inaugurated as President of the United States, what length-by-width-by-height console size in inches did Sears, Roebuck and Co. list in its Christmas catalog for the Tele-Games Video Arcade unit that meets all of the following:

- includes the Target Fun cartridge
- comes with two joysticks and two paddle controls
- is sold under a Sears catalog number in the 6 C 997 series

## Answer
14 x 9 1/2 x 3 3/4 inches

## Golden Trajectory
Step 1 — Identify the catalog year
Search: "Jimmy Carter inaugurated date Miller Center"
Fetch: https://millercenter.org/president/carter/key-events
Verify: On the Miller Center Jimmy Carter Key Events page, locate the entry dated January 20, 1977 titled “Carter inaugurated.” Confirm that Carter was inaugurated as the thirty-ninth President of the United States on that date. The calendar year is therefore 1977, so the Sears Christmas catalog for this ask is the 1977 book.

Step 2 — Locate the 1977 Sears Christmas Book
Search: "1977 Sears Christmas Book christmas.musetechnical"
Fetch: https://christmas.musetechnical.com/ShowCatalog/1977-Sears-Christmas-Book
Verify: Confirm the catalog title/year is the 1977 Sears Christmas Book. Use this page only as a catalog locator. Do not treat Muse image-viewer pages as the decisive size source.

Step 3 — Extract the Video Arcade console size from searchable OCR text
Fetch: https://christmas.musetechnical.com/202510/Catalogs.Api/api/CatalogPageByCatalogNameAndCatalogPageNumber?strCatalogName=1977-Sears-Christmas-Book&strCatalogPageNumber=2
Verify: Open the Muse Catalogs.Api JSON for catalog page 2 (VIDEO ARCADE / COLOR TELE-GAMES). This response is plain UTF-8 JSON with a usable text layer in the `pageOCRWords` field (selectable / findable with Ctrl+F), not the image-only ShowCatalogPage viewer. In `pageOCRWords`, locate the Video Arcade CONSOLE listing that includes Target Fun, 2 joystick and 2 paddle controls, catalog 6 C 99743, and highlight these exact strings:

- `CONSOLE: Streamlined impact-resistant plastic console 14x91/2x33/4 in. high.`
- `6 C 99743-Shipping weight 6 pounds 5 ounces`

The printed length-by-width-by-height console size is 14 x 9 1/2 x 3 3/4 inches. Do not invent 14 1/2 x 9 x 4 inches from a secondary owner’s manual, do not invent 14 x 9 1/4 x 3 3/4 inches from garbled secondary OCR, and do not substitute the same-listing shipping weight (6 pounds 5 ounces) or cash price (178.95 dollars). Do not use the image-only URL `ShowCatalogPage/.../2` as the answer source.

✅ Final answer
14 x 9 1/2 x 3 3/4 inches

## Verification Sources
1. https://millercenter.org/president/carter/key-events
2. https://christmas.musetechnical.com/ShowCatalog/1977-Sears-Christmas-Book
3. https://christmas.musetechnical.com/202510/Catalogs.Api/api/CatalogPageByCatalogNameAndCatalogPageNumber?strCatalogName=1977-Sears-Christmas-Book&strCatalogPageNumber=2

Decisive Ctrl+F string in source 3 `pageOCRWords`:
`CONSOLE: Streamlined impact-resistant plastic console 14x91/2x33/4 in. high.`

## Failure justification
ChatGPT names 14 1/2 x 9 x 4 inches as the Wish Book console size for the Sears Tele-Games Video Arcade, citing an Atari Compendium owner’s-manual PDF instead of the catalog listing. That figure does not appear on the printed page. In the Muse Catalogs.Api OCR text for catalog page 2 of the 1977 Sears Christmas Book (`pageOCRWords`), the Video Arcade unit with Target Fun, two joysticks and two paddle controls (catalog 6 C 99743) lists `14x91/2x33/4 in. high`, i.e. 14 x 9 1/2 x 3 3/4 inches, so the model substituted a secondary manual measurement for the asked catalog size.
