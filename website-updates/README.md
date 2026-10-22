# Philly location page update

These four HTML files are an overlay for the existing PHP website supplied in `Philly website 22-10-26 update.zip`, not a complete standalone site. Copy the `nl/` and `en/` subdirectories over the corresponding paths in the existing web root after backing them up. Do not deploy this repository root or the website-updates directory as the entire website.

Adds Dutch and English value copy to both location pages: ribeye, cheese choices, freshly baked bread, Classic €15, beef combo €20 and chicken combo €18. Website prices checked against the supplied current menu on 22 October 2026; channel differences are stated. Existing addresses, opening hours, schema, styling references, navigation and checkout links are preserved.

Pending: verified direct Google review links for each branch. Existing address-based map links have not been relabelled as review links. No rating counts or portion weights were invented. Restaurant Guru correction remains unsubmitted.

Validation: parsed embedded JSON-LD on all four pages, checked every root-relative link target against the supplied source, and verified one value-section ID per page. Browser visual QA and live deployment have not been performed.

Only these public HTML pages and this README were committed. Payment configuration, staff/order data, admin code and older deployment copies from the supplied archive were not uploaded.
