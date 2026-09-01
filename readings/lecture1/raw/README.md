# Lecture 1 — Raw readings

All six documents present. Sources fetched 2026-09-01.

| File | Reading | Source |
|---|---|---|
| `yu-barter_ch1_veridical-data-science.html/.txt` | Yu & Barter, *Veridical Data Science*, Ch. 1 | vdsbook.com (open-access web edition, CC BY-NC-ND) |
| `yu-barter_ch2_data-science-life-cycle.html/.txt` | Yu & Barter, Ch. 2 | vdsbook.com |
| `yu-barter_ch3_code-reproducibility.html/.txt` | Yu & Barter, Ch. 3 | vdsbook.com |
| `box1976_science-and-statistics.pdf/.txt` | Box (1976), "Science and Statistics", *JASA* 71(356):791–799 | open copy; JSTOR stable/2286841 |
| `degroot1987_conversation-with-george-box.pdf` | DeGroot (1987), "A Conversation with George Box", *Statist. Sci.* 2(3):239–258 | Project Euclid (scanned; no text layer — read as page images) |
| `Wallis-StatisticalResearchGroup-1980.pdf` + `wallis1980_statistical-research-group.txt` | Wallis (1980), "The Statistical Research Group, 1942–1945", *JASA* 75(370):320–330 | supplied via Berkeley JSTOR access |

`.txt` files are extracted plain text for searching. The Wallis text was extracted
column-aware (PyMuPDF blocks sorted left column then right); plain `pdftotext -layout`
interleaves the two columns and is unreadable.

The DeGroot PDF has no text layer, so there is no `.txt` for it. Pages 20–25 of that
file are high-resolution photo plates, not article text; the article itself is pp. 239–258.
