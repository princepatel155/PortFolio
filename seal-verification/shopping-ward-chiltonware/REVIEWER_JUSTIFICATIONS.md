# Reviewer Justifications — Shopping / 1959 Ward Chiltonware

## Reply — Major (Sujal): image-only Muse page / no Ctrl+F text layer

**Suggestion:** The catalog page is a scanned image with no usable text layer, so the price cannot be highlighted or found with Ctrl+F. Since the answer is only readable visually and no searchable version exists, the source is not compliant. The 3rd source (`ShowCatalogPage/.../350`) is a scanned image with no usable text layer.

**Change made:**
1. **Removed the image-only ShowCatalogPage URL from GT/VS** as the decisive answer source.
2. **Replaced it with Muse’s Catalogs.Api page payload** for the same catalog page 350:
   `…/202510/Catalogs.Api/api/CatalogPageByCatalogNameAndCatalogPageNumber?strCatalogName=1959-Montgomery-Ward-Christmas-Book&strCatalogPageNumber=350`
   That endpoint returns `application/json` with a plain-text `pageOCRWords` field containing the Chiltonware listing and cash price (`48 T 4767` … `21-Pc. Set 2.77`). The text is selectable and findable in the browser (usable text layer), addressing the no-Ctrl+F / no-highlight objection.
3. Kept the Muse `ShowCatalog` URL only as a catalog-title locator, not as the price extract.
4. Kept Eisenhower Hawaii statehood for the calendar hop.
5. Answer remains plain **2.77 dollars** (not `$2.77`).

## Why not archive.org
Internet Archive hosts a searchable text PDF of this catalog, but archive.org / Wayback are banned for GT/VS. No Google Books volume with this catalog was available to substitute.

## Why this price is inventable
Confirmed ChatGPT fail: invented **5.98 dollars** while citing only the Muse catalog root, without reading the Chiltonware listing priced at **2.77 dollars**.
