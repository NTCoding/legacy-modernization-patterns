---
title: "Bi-directional Sync"
description: "Write operations occur in both new and legacy and are synced in both directions"
featured: "/patterns/data-synchronisation/bi-directional-sync/bi-directional-feature.svg"
subtitle: false
menu:
  doc:
    name: Bi-directional Sync
    parent: data-synchronization
    pre: sync_alt
categories: [data-synchronization]
tags: []
weight: 3
---

Bi-directional sync involves write operations happening in both the new and legacy system for the same conceptual data like updating the same booking. Since both systems are able to modify the same information, they both need an upto date copy in their local datastore. Therefore, any write operation on side must be synchronised across to the other.

<div class="title title--sans title--third">
  <img src="/patterns/data-synchronisation/bi-directional-sync/bi-directional-feature.svg" alt="Bi-directional Sync Pattern" style="max-width: 100%; width: 100%; height: auto;">
</div>

{{< comingsoon >}}
