readme_orphans_to_del.txt
Patent_Exam repository — files no longer referenced by any page
Prepared 9 September 2026, after the abridged-edition upgrade.

HOW THIS LIST WAS BUILT
-----------------------
Every .html file in the repo was parsed and every src= and href= value
collected, including same-site absolute URLs of the form
https://marti124.github.io/Patent_Exam/<file>. That set of referenced
names was compared against the actual file list. Anything present on
disk but absent from the reference set is listed below.

Handout_*.pdf and X_Testimonials.pdf were excluded from this analysis
at your instruction; you are handling those separately.


=========================================================
SECTION 1 — SAFE TO DELETE (5 files, 1.71 MB)
=========================================================
These are Chapter 1 figures from the two-volume edition. The abridged
Chapter 1 carries five figures where the old one had eight, and the
surviving images were renamed into document order. Nothing on the site
points at any of these.

    ch1_fig3.png      121,887 bytes
    ch1_fig5.png      248,047 bytes
    ch1_fig6.png      282,240 bytes
    ch1_fig7.png      182,872 bytes
    ch1_fig8.png      879,691 bytes

Note on ch1_fig3.png: its content is not lost. It is byte-identical to
the new ch1_fig2.png, which the rebuilt Chapter 1 page now uses in the
second figure position. Deleting the old name discards a duplicate.

The other four images do not appear anywhere in the abridged chapter.
If you want them preserved outside git history, copy them somewhere
before deleting.


=========================================================
SECTION 2 — CHECK BEFORE DELETING (2 files)
=========================================================
Unreferenced by any page, but each looks deliberate rather than
abandoned. Do not delete without deciding what it is for.

    Forgotten_Half_Invitation_to_Review_PRINT.html
        A print-formatted twin of the Invitation. Nothing links to it,
        which is normal for a print variant handed out by direct URL.

    Forgotten_Half_Invitation_to_Review.pdf
        A PDF of the same document. May be distributed by link or
        email rather than from the site.

    RESOLVED 9 Sep 2026 — The_Forgotten_Half_of_the_Patent_Clause_Exam_Score_Page.pdf
        Not an orphan. This is the sheet a reader prints and scores by
        hand in pen or pencil while running the examination. It is now
        linked directly from the exam chapter page, under the heading
        "Reason It Yourself". Keep it.


=========================================================
SECTION 3 — DO NOT DELETE
=========================================================
These appear unreferenced to a naive scan but are all required.

    index.html
        The landing page. Nothing links to it because it is the entry
        point.

    README.md
        GitHub repository readme.

    Forgotten_Half_Chapter_9.html
    Forgotten_Half_Chapter_34.html
    Forgotten_Half_Mini_Preface.html
    Forgotten_Half_Two_Volume_Brief.html
        Retained deliberately as forward-pointing aliases. Each holds
        the current abridged content and links onward to the new
        filenames. They exist because other sites may still link to
        the old URLs. Keep until those inbound links are updated.

    Forgotten_Half_Chapter_34.pdf
    Chapter_34_..._EXAM_ATTACHMENT.pdf
    Chapter_34_..._EXAM_ATTACHMENT.docx
    Chapter_34_..._EXAM_SCORE_PAGE.pdf
        Same reasoning: old-name copies kept alongside the new
        Chapter_28 names.

    banner.jpg
    brief_fig1.png, brief_fig2.png, brief_fig3.png
    ch1_fig1.jpg, ch1_fig2.png, ch1_fig3.jpg, ch1_fig4.png, ch1_fig5.jpg
        All in active use.


=========================================================
CAVEAT
=========================================================
Three pages had not yet been rebuilt when this list was prepared:
Forgotten_Half_Two_Volume_Brief.html,
Forgotten_Half_Invitation_to_Review.html, and index.html. None of them
references any Chapter 1 figure, so Section 1 is unaffected. Re-run the
reference scan after those three land if you want the list confirmed
against the finished site.
