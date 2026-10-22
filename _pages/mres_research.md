---
title: "AI4H Lab - MRes Research"
layout: textlay
excerpt: "AI4H Lab -- MRes Research"
sitemap: false
permalink: /mres_research/
---

# MRes Research

Masters-level research projects carried out with the group at the Institute of Health Informatics.

## Wrist-Cuff Smartwatches for Ambulatory Blood Pressure Monitoring (Huiqian Wu)

*MSc Health Data Science dissertation, 2026. Supervisor - Dr Kezhi Li.*

High blood pressure and diabetes often go together, and each makes the other more dangerous. The standard way to track blood pressure across a whole day is ambulatory monitoring with an upper-arm cuff. It works, but it is uncomfortable, it disturbs sleep, and it is rarely worn for more than 24 hours. That leaves us with almost no picture of how blood pressure moves over several days of ordinary life. A new generation of smartwatches carries a real inflatable cuff shrunk down to the wrist, so it can be validated against the same clinical standards as a conventional monitor. The open question is not whether the watch can measure, but whether people will keep wearing it.

This project put that question to the test. Six adults took part: two with type 1 diabetes, two with type 2 diabetes and two without diabetes, all of them already using a continuous glucose monitor. Each wore a **Huawei Watch D2** during the day for three weeks, taking a blood pressure reading roughly every 45 minutes, while their glucose sensor ran as usual. At the end they completed a questionnaire covering sixteen rated items and several open questions. The ratings were summarised item by item, and the written answers were analysed for recurring themes.

![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/mres_smartwatch_bp.png){: style="width: 90%; float: center; margin: 10px"}

Everyone finished the three weeks, nobody dropped out, and five of the six said they would use this kind of watch outside a research study. The problem was not wearing the watch. It was taking the measurement. Readings failed during walking, driving and even after a short walk, and the fixed 45-minute cycle demanded that people stop, sit still and raise an arm at moments that did not suit them: in meetings, at the wheel, or on a hospital ward where staff are not allowed to wear anything below the elbow. Of all sixteen items, **measuring during physical activity scored lowest**, and three of the six participants rated it 2 or below.

That finding matters more than a simple comfort complaint. If readings fail mostly while people are active, the missing data is not random, and the very periods a free-living study wants to capture are the ones most likely to go missing. The work recommends that future deployments use motion-tolerant measurement with automatic retries, allow a reading to be delayed by a few minutes rather than fixing it to a rigid clock, and record objective logs of how many scheduled readings actually succeeded.

Analysis code and the study questionnaire are available on [GitHub](https://github.com/Scallop233/smartwatch-bp-feasibility){:target="_blank"}{:rel="noopener noreferrer"}. The study was approved by the UCL Life and Medical Sciences Research Ethics Committee (ID 2680).
