Step 1 — Identify the catalog year
Search: "Hawaii admitted as a state date Eisenhower Library"
Fetch: https://www.eisenhowerlibrary.gov/research/online-documents/hawaii-statehood
Verify: On the Eisenhower Library Hawaii Statehood page, in the introductory narrative paragraph under the page heading (before the document list), confirm that on August 21, 1959 President Eisenhower signed the official proclamation admitting Hawaii as the 50th state. The calendar year of admission is therefore 1959, so the Sears Christmas catalog for this ask is the 1959 book.

Step 2 — Locate the 1959 Sears Christmas Book
Search: "1959 Sears Christmas Book christmas.musetechnical"
Fetch: https://christmas.musetechnical.com/ShowCatalog/1959-Sears-Christmas-Book
Verify: Confirm the catalog title/year is the 1959 Sears Christmas Book. Use this page only as a catalog locator. Do not treat Muse image-viewer pages as the decisive price source.

Step 3 — Extract the Gun Rack cash price from searchable OCR text
Fetch: https://christmas.musetechnical.com/202510/Catalogs.Api/api/CatalogPageByCatalogNameAndCatalogPageNumber?strCatalogName=1959-Sears-Christmas-Book&strCatalogPageNumber=416
Verify: Open the Muse Catalogs.Api JSON for catalog page 416 (children’s cap-gun / play-weapons page). This response is plain UTF-8 JSON with a usable text layer in the `pageOCRWords` field (selectable / findable with Ctrl+F), not the image-only ShowCatalogPage viewer. In `pageOCRWords`, locate the Western-style Gun Rack listing and highlight these exact strings:

- `Western-style Gun Rack teaches neatness $3.39`
- `Stained pine with burned-in effect western design. 20 in. wide, 201/2 in. high.`
- `8 hooks for 4 rifles, 3 pegs for hats or pistols`
- `79 N 02683-Partly assembled. Shipping weight 4 pounds .... . $3.39`

The cash price on that listing is 3.39 dollars. Nearby same-page prices in the OCR text (2.89 dollars, 1.93 dollars, 2.79 dollars, and similar) are different items. Do not invent 2.98 dollars. Do not use the image-only URL `ShowCatalogPage/.../416` as the answer source.

✅ Final answer
3.39 dollars
