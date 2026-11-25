# Browser and data validation

The interface was tested in a Chromium browser with in-memory HTML/CSS/JavaScript injection because the test environment blocks normal local network navigation. This confirms the visible interface, event handlers and client logic, but **not live GitHub Pages PDF rendering or browser storage persistence**.

Verified in test: question library search, source filtering, subject and subtopic filters, practice builder, 20-question session, subject rotation, 110-question timed session, timed-score submission, untimed per-question answer submission, solution reveal, next-question navigation, optional source-frame toggle, and narrow-screen layout without horizontal page overflow. JavaScript error log: none.

Automated checks: 2,294 indexed questions, 221 exact companion topic matches, 65 existing redrawn diagram cards, six valid source PDF files, no nested ZIP files and no file larger than 25 MiB. Neither the published CDN renderer nor the engineering correctness of all source answers was independently verified.
