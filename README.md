# Data Visualization and Storytelling

SDAIA Academy · SDA-DSC-112

SDAIA Academy GitHub: https://github.com/SDAIAAcademy

## Group

- Abdulaziz Al-Abdulkareem — https://github.com/owAziz
- Khalid Aljohar — https://github.com/aljokha

## What we did

This repository holds a seven-slide executive briefing on where to direct the next SAR 40 million so lagging regions move toward the 65% digital-adoption target.

National adoption is already past the target: 66.2% in December 2025, and above 65% since August 2025. Eight of 13 regions are still below 65%. Four of those are 2 to 4 points short: Najran, Northern Borders, Al-Baha, and Jazan. The other four are under a point away.

The ask is to approve one split: divide the 40 million by the size of each gap, across only those four regions.

- Najran: SAR 15.6 million
- Northern Borders: SAR 8.7 million
- Al-Baha: SAR 8.3 million
- Jazan: SAR 7.4 million

The deck is `Tayseer_Capstone.pptx`. Slide 1 states the ask. Slides 2–6 cover the national situation, the regional gap, the evidence, the options, and the recommendation. Slide 7 repeats the ask and sets a June 2026 checkpoint on the dashboard. One appendix slide shows how the numbers were calculated.

## The dashboard

The evidence comes from this Tableau Public dashboard:

https://public.tableau.com/app/profile/abdulaziz.alabdulkareem/viz/digitaladoption/Tayseer-DigitalAdoption

Adoption is weighted by unique users: the sum of (digital adoption % × unique users), divided by total unique users. That is the same calculated field as the dashboard. The December 2025 KPI and the regional chart on the slides are taken from it.

## Tools

- Tableau Public, for the dashboard
- Microsoft PowerPoint, for the seven-slide story
- Python (pandas, matplotlib, python-pptx), to calculate the gap split and build the trend, annotated-gap, and options charts on the slides
