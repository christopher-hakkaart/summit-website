---
slug: one-link-to-rule-them-all
title: "One Link to Rule Them All"
url: https://quiltdata.com
image: ../../../images/visuals/poster.png
poster_id: 19
speakers:
  - Ernest Prabhakar
tags:
  - Ecosystem
---
<div className="mb-8">
  <small className="typo-small">
    Ernest Prabhakar, Aneesh Karve, Kevin Moore, Robert Newman
  </small>
</div>

Most pipelines read and write from local files -- or at best, cloud URLs.
This makes it impossible to know (much less prove) exactly which data
generated a given result. We use Quilt packages to add ""canonicity""
to NextFlow pipelines, enabling:

- Reproducibility
- Portability
- Auditability
- Fearless Sharing

The key to this the Quilt URI, a "unique digital fingerprint" built from
cryptographically-secure hashes of a collection of data files
at a specific point in time. Our open source code uses Quilt URIs
to track data lineage across the complete end-to-end pipeline, generating
an unbreakable chain of custody suitable for use in, e.g., IND filings.
