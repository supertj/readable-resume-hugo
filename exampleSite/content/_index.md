+++
# Everything on your resume lives in this file. Save it while `hugo server`
# is running and the page reloads.
#
# Inline Markdown works in the contact line and in every field under
# [[params.sections]]: **bold**, *italic* and [links](https://example.com).
# Your name and the text of a contact link are printed as typed.

# Your name, printed at the top and used in the browser tab
title = "Olivia Bennett"

# The meta description. Search engines may show it in results if you put the
# page online
description = "Resume of Olivia Bennett, an economics student at Halden College."

[params]
# Joined with vertical bars. Email addresses and full https:// links become
# clickable. To show shorter text for a link, give it a url:
#   { text = "github.com/oliviabennett", url = "https://github.com/oliviabennett" },
contact = [
  "Providence, RI",
  "(401) 555-0132",
  "olivia.bennett@example.com",
  "linkedin.com/in/oliviabennett",
]

# Sections print in the order they appear here. Each entry is laid out by
# whether it has a school, a company or a name field.

[[params.sections]]
title = "Education"

[[params.sections.entries]]
school = "Halden College"
location = "Providence, RI"
degree = "Bachelor of Arts in Economics, Minor in Statistics"
date = "Sep 2022 – May 2026"
bullets = [
  "GPA: 3.8/4.0, Economics Department Honors Program",
  "Relevant Coursework: Econometrics, Corporate Finance, Game Theory, Financial Accounting, Data Analysis in Python",
]

[[params.sections]]
title = "Experience"

[[params.sections.entries]]
company = "Harlan Quay Capital Partners"
location = "New York, NY"
title = "Investment Banking Analyst Intern"
date = "Jun 2025 – Aug 2025"
bullets = [
  "Built three-statement models for two consumer retail clients and updated comparable company sets each week",
  "Drafted 20 pages of a sell-side pitch book, including the industry overview and buyer list",
  "Checked a 40-tab merger model line by line before it went to the client and found a circular reference in debt schedules",
]

[[params.sections.entries]]
company = "Halden College Department of Economics"
location = "Providence, RI"
title = "Research Assistant"
date = "Jan 2024 – May 2025"
bullets = [
  "Cleaned and merged 15 years of county wage data in Stata for a professor's study on minimum wage spillovers",
  "Wrote summary tables and charts that appeared in a working paper presented at two conferences",
]

[[params.sections.entries]]
company = "Halden College Writing Center"
location = "Providence, RI"
title = "Peer Tutor"
date = "Sep 2023 – Dec 2024"
bullets = [
  "Met with about eight students a week to work on essays, lab reports and cover letters",
  "Led two workshops on writing clear policy memos for first-year economics students",
]

[[params.sections]]
title = "Projects & Activities"

[[params.sections.entries]]
name = "Halden Investment Club"
role = "Vice President"
date = "Sep 2023 – Present"
bullets = [
  "Run weekly stock pitch meetings for 45 members and manage a $25,000 student portfolio with four sector heads",
  "Started a mentoring program that paired 18 first-year members with alumni working in finance",
]

[[params.sections.entries]]
name = "Halden Habitat Builders"
role = "Volunteer Coordinator"
date = "Sep 2022 – May 2024"
bullets = [
  "Organized monthly build days for about 30 volunteers and kept the sign-up and safety records",
]

[[params.sections]]
title = "Skills"
# One per line. A label prints in bold, followed by a colon.
lines = [
  { label = "Technical", text = "Excel, PowerPoint, Python (pandas), Stata, Capital IQ" },
  { label = "Certifications", text = "Bloomberg Market Concepts, Wall Street Prep Financial Modeling" },
  { label = "Languages", text = "French (fluent), Spanish (basic)" },
]
+++
