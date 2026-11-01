## Project: Healthcare Data Breach Analysis (2023–2024)

For my project, I want to investigate whether hacking-related healthcare data breaches typically affect more people than unauthorized access or disclosure incidents in the United States. Cybersecurity is a growing concern nowadays, with frequent news about vulnerabilities, cyberattacks, and data leaks. This topic is personal to me because some of my information was leaked on the dark web, and someone attempted to misuse my identity. This experience encouraged me to learn more about cybersecurity and data privacy. I am also interested in healthcare because hospitals store large amounts of sensitive patient information, making them attractive targets for hackers. I chose 2023–2024 because the data is relatively recent, and most reports from these years are already archived. I collected the data from the U.S. Department of Health and Human Services (HHS) and will use permutation testing and bootstrapping to compare the two breach categories.

## Project Scaffold Table

| Element | My Plan |
|---|---|
| **Topic / Question** | Are hacking-related healthcare data breaches typically larger than unauthorized access/disclosure breaches in the U.S. during 2023–2024? |
| **Hypothesis** | I expect hacking-related breaches to affect more people per reported incident than unauthorized access/disclosure breaches. |
| **Outcome / Metric / Test Statistic** | Number of individuals affected per breach. I will compare the difference in median affected-person counts between the two groups. |
| **Units of Analysis** | Each observation represents one reported healthcare data breach notification. |
| **Data Source(s)** | U.S. Department of Health and Human Services (HHS), [HIPAA Breach Reporting Portal](https://ocrportal.hhs.gov/ocr/breach/breach_report_hip.jsf). Reports submitted during 2023–2024 from the Archive and Under Investigation sections. |
| **Why This Data Works** | The dataset contains 1,486 reports, including 1,445 in my two comparison groups. It provides breach types and affected-person counts needed for the analysis. |
| **Uncertainty Metric** | I will use bootstrapping to estimate 95% confidence intervals for the mean and median differences. The median difference is my non-CLT metric. |
| **Null Hypothesis** | Under the null model, breach size is unrelated to breach type within each submission year. Any observed difference could be due to random variation. |
