---
title: "Upcoming Change: U4 firmAssociations.officeLocations Address Behavior"
url: "https://developer.finra.org/news/upcoming-change-u4-firmassociationsofficelocations-address-behavior"
date: "2026-10-05"
author: "K29547"
feed_url: "https://developer.finra.org/rss.xml"
---
Upcoming Change: U4 firmAssociations.officeLocations Address Behavior K29547 Mon, 10/05/2026 - 14:29 An upcoming change is being made to how U4 location addresses are handled. Please review the behavior below: Registered Locations (Main Office / Locations with Branch CRD): Any address provided via U4 submissions under firmAssociations.officeLocations will be ignored — the existing registered address will be retained. Note that previously, if bdMainOfficeIndicator was set to true for a location, the branch was receiving the main office address.
