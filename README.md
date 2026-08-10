# blog — retired

> **This repo is no longer used. Pushing here does nothing to the site.**

The posts moved to
[jebin2/jebin2.github.io](https://github.com/jebin2/jebin2.github.io) under `content/`,
with their full git history — so the publication dates, which come from each file's first
commit, came along with them.

Write posts there now:

```
content/C/Bitfields/Bitfields.md
```

Push to `main` and the site builds and deploys itself. See that repo's README.

## Why

The site used to fetch these files at read time through the jsDelivr CDN, which meant a
cross-repo trigger to rebuild, a personal access token, and a cache-purge step after every
publish — all of it there only because the words and the site lived apart. Merging them
removed the trigger, the token, the purge, and the CDN staleness they worked around.

This repo is kept as the original history. Nothing here is live.
