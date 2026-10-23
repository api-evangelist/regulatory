---
title: "API Platform August 18, 2026 Release Notes"
url: "https://developer.finra.org/release-notes/api-platform-august-18-2026-release-notes"
date: "2026-08-18"
author: "K29547"
feed_url: "https://developer.finra.org/rss.xml"
---
API Platform August 18, 2026 Release Notes K29547 Tue, 08/18/2026 - 15:46 U4 , U5 , and BR Submissions Added field-name validation to U4, U5, and BR submissions. Requests containing invalid or misspelled field names — including invalid fields within nested objects — are now rejected before processing. Previously, invalid fields were silently accepted, which could result in filings being submitted successfully without the intended changes applied.
