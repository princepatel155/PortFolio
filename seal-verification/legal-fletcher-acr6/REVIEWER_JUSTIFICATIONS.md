# Reviewer Justifications — Fletcher ACR 6 / Mrs. Vernon C. Hawk (Dipesh)

---

## Reply 1 — Minor: URLs from steps 3–5 not accessible; add search terms in step 3

**Suggestion:** The URLs provided from step 3 to step 5 are not accessible. Also, in step 3 state the search terms (e.g. "State Mother") needed to navigate and locate the correct section within the document.

**Change made:** Steps 3–5 (and matching Verification Sources) initially used clean Chief Clerk PDF URLs with ordinary underscores (`59Vol1_Measures.PDF`, `59Vol2_Chapters.pdf`) and `#page=` deep links. That accessibility fix is retained for the surviving Vol. 2 corroboration URL; the Measures-table search path was later removed (see Reply 3).

---

## Reply 2 — Major: URLs in steps 3, 4, 5 are not working

**Suggestion:** URLs in steps 3, 4, and 5 are not working.

**Change made:** The broken links were caused by Markdown/LaTeX-escaped underscores in the PDF filenames (`59Vol1\_Measures.PDF` and `59Vol2\_Chapters.pdf`), which return HTTP 404 on clerk.assembly.ca.gov. Those escapes are removed. The surviving Chief Clerk corroboration URL uses an ordinary underscore and returns HTTP 200:

`https://clerk.assembly.ca.gov/sites/clerk.assembly.ca.gov/files/archive/Statutes/1959/59Vol2_Chapters.pdf#page=2370`

---

## Reply 3 — Major (Arnav): Table of Resolutions PDF is image-only; remove Ctrl+F; provide searchable official source for ACR No. 6 / Mrs. Vernon C. Hawk

**Suggestion:** The revised GT is still not reproducible because the Table of Resolutions PDF is image-only. “State Mother” and “Waverley” cannot be searched in that document, and the table itself does not list resolution subjects. Please remove the Ctrl+F/search instruction and provide a searchable official source that identifies ACR No. 6 and directly verifies Mrs. Vernon C. Hawk.

**Change made:**
1. Removed the Chief Clerk `59Vol1_Measures.PDF` Table of Resolutions step and all Ctrl+F / in-PDF keyword-search instructions against that image-only scan.
2. Added the searchable HathiTrust full-view OCR of the official *Statutes of California* 1959 v.2 (University of Minnesota; htid `umn.31951d02287782u`), reached via catalog Record `010587406`.
3. Identification of ACR No. 6 is now done with the HathiTrust OCR query  
   `q1="Assembly Concurrent Resolution No. 6"`  
   which lands on Chapter 18 / ACR No. 6 relative to the death of Mrs. Ed. Fletcher and includes the 1949 State Mother / Waverley findings in the same OCR text.
4. Direct verification of the Lockport daughter is done with the HathiTrust OCR query  
   `q1="Mrs. Vernon C. Hawk"`  
   which returns the survivors enumeration naming **Mrs. Vernon C. Hawk of Lockport, New York**.
5. Kept one Chief Clerk Vol. 2 deep link (`#page=2370` / printed p. 5392) only as official California Assembly corroboration of that same survivors line — not as a keyword-search path.
