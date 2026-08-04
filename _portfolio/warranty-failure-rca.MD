---
title: "Warranty Failure Root Cause Analysis"
excerpt: "Two years of warranty repairs measured against shipment records to find why units came back, and to prove the corrective actions actually worked."
weight: 2
header:
  image:
  teaser: /assets/img/warranty-method.svg
gallery:
  - url: /assets/img/warranty-method.svg
    image_path: assets/img/warranty-method.svg
    alt: "Five-step analysis pipeline: warranty log, classify by fix, join to shipments, drop bad months, check the lag"
  - url: /assets/img/warranty-trend.svg
    image_path: assets/img/warranty-trend.svg
    alt: "Line chart of PCB and switch warranty claim rate, indexed to Q1 2025, six quarters"
---

<!-- TODO Luke: CLEARANCE NEEDED BEFORE PUBLISHING.
     This page contains no absolute defect rates, no unit volumes, no product names,
     and no board part numbers, because those are COCCO business data. The trend chart
     goes a step further and shows the shape of the quarterly trend (indexed, not
     absolute), which is more than the bullet list alone discloses. Confirm your
     employer is comfortable with this before it goes live. -->

![Analysis pipeline](/assets/img/warranty-method.svg)

*Product Development Engineer &middot; COCCO Hair Professional &middot; 2024&ndash;2026*

# The problem

Units were coming back from the field, and the two loudest complaints were "no power" and a broken power switch. Both had been treated as one-off hardware repairs. Nobody had asked the harder question: across everything that came back, what is actually breaking, and is it getting better?

The repair log had two years of history, but only as a list of individual jobs — never something you could draw a conclusion from.

# Constraints

* Returns were never tied to serial numbers or ship dates, so a failure could not be traced back to the batch it came from
* The log used free text, so the same fault was written a dozen different ways
* Sales volume was climbing steeply over the period, so a raw repair count would understate any real improvement
* Several months of the log were missing outright

# Approach

I classified every repair by what the technician actually replaced, not what the customer reported — "no power" alone was ambiguous between a dead board, a dead battery, and a switch not making contact, but the fix told the real story. I then joined the repair log to shipment records so failures became a rate per unit shipped instead of a raw count, since volume nearly doubled over the period. Months with missing data were excluded rather than zeroed, and I re-ran the comparison against units shipped three and six months earlier to make sure the trend wasn't an artifact of growing volume.

# What it found

Working with the contract factory to isolate the cause, we traced the dominant "no power" failure to firmware rather than hardware — most of those units were fixed by reflashing the board, not replacing it. I helped drive and test the corrective board revision, and reflash repairs disappeared once it shipped.

The switch failures were mechanical: the recurring note was sheared switch pins alongside a cracked bottom cap, a load-path problem rather than a contact one, which drove a redesign of the switch mechanism.

A separate teardown of one returned lot also found that more than one in five units had nothing wrong with them — a returns-handling problem, not an engineering one.

# Results

* PCB-related warranty claims per unit shipped fell **84%** year over year
* Switch-related claims fell **55%** over the same period
* Total warranty claims per unit shipped fell **81%**, while shipment volume grew
* The failure modes were designed out of the next-generation product

![Warranty claim rate trend, indexed to Q1 2025](/assets/img/warranty-trend.svg)

# What I would change

I'd push for serial-number traceability from the start. Without it, I could measure that things improved but never cleanly attribute the improvement to a specific design change — everything above is a rate per unit shipped, not a true cohort failure rate. A structured fault code at the repair bench, instead of free text, would have saved most of the classification work too.

# Tools

Python, pandas, warranty and ERP data, root cause analysis, supplier 8D review

{% include gallery caption="" %}
