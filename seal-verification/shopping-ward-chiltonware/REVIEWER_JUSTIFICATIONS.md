# Reviewer Justifications — Shopping / 1959 Ward Chiltonware

## Reply 1 — Major (Sujal): answer source is scanned image / no usable text layer

**Suggestion:** The answer source does not meet the requirements. The catalog page is a scanned image with no usable text layer, so the price cannot be highlighted or found with Ctrl+F. Since the answer is only readable visually and no searchable version exists, the source is not compliant for this task.

**Reply / change made:**
Agreed. The prior decisive source was Muse’s image viewer (`ShowCatalogPage/.../350`), which is a scan with no usable text layer. That URL has been removed as the answer source. GT/VS now use Muse’s Catalogs.Api JSON for the same catalog page 350:

`https://christmas.musetechnical.com/202510/Catalogs.Api/api/CatalogPageByCatalogNameAndCatalogPageNumber?strCatalogName=1959-Montgomery-Ward-Christmas-Book&strCatalogPageNumber=350`

That endpoint returns `application/json` with a plain-text `pageOCRWords` field. The Chiltonware cash price is findable/highlightable there as: `48 T 4767-Ship. wt. 1 lb .... .. 21-Pc. Set 2.77`. Answer remains **2.77 dollars**. Eisenhower Hawaii statehood and the Muse catalog root are kept only for the year/catalog hop, not as the price extract.

## Reply 2 — Major (Sujal): 3rd source is scanned image / no Ctrl+F

**Suggestion:** 3rd source is a scanned image with no usable text layer, so the price cannot be highlighted or found with Ctrl+F.

**Reply / change made:**
Agreed. The 3rd VS URL was the image-only `ShowCatalogPage/.../350` viewer and has been replaced. The new 3rd source is the Muse Catalogs.Api page payload above (`application/json`), whose `pageOCRWords` text layer contains the selectable listing for catalog `48 T 4767` / `21-Pc. Set 2.77`. GT ↔ VS still match exactly on the three URLs; no archive.org / HathiTrust / Wikipedia sources were added.
