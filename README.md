
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Project Overview

This project is aimed at improving the decision-making processes within
*Educate Plus*, a professional association dedicated to the advancement
of education professionals across Australasia.

The objective of this project is to design and implement three
interactive, real-time dashboards to provide clear, actionable insights
to various departments within *Educate Plus*, such as marketing,
finance, and events. These dashboards - **Members Dashboard**,
**Membership Dashboard**, and **Events Attendance Dashboard** enable
stakeholders to track key performance indicators (KPIs) and make
data-driven decisions to improve member engagement and optimize event
planning.

## Key Features:

1.  **Members Dashboard**: Provides insights into the total number of
    active members, renewal trends, and member engagement.
2.  **Membership Dashboard**: Tracks the count of new, current and
    lapsed members, identifying patterns to re-engage lost members.
3.  **Events Attendance Dashboard**: Visualizes attendance trends at
    events, comparing engagement between members and non-members.

## Tools and Technologies

The project leverages the following tools:

- **CiviCRM**: The primary source of membership and event data for
  Educate Plus. CiviCRM is a customer relationship management platform
  tailored for nonprofit organizations.

- **Looker Studio (Google Data Studio)**: Looker Studio is used to
  create interactive dashboards that visualize processed data, allowing
  Educate Plus to monitor real-time KPIs.

- **R**: R was mainly used for Initial Data Analysis (IDA), providing a
  structured approach to explore and clean the data, as well as for
  keeping logs of all work completed during the project.

  - `dplyr` for data manipulation and transformation (e.g., filtering,
    grouping, and summarizing data).
  - `readr` for reading and writing CSV files.
  - `tidyr` for data tidying and reshaping.
  - `kable` (from `knitr`) to display data summaries in well-formatted
    tables for reporting purposes.

You can install the required packages using the following R command:

``` r
install.packages(c("dplyr", "readr", "tidyr"))
```

## License

This project is licensed under the MIT License, a permissive open-source
license. This means that you are free to use, modify, and distribute the
code, as long as the original copyright notice and this permission
notice are included in all copies or substantial portions of the
software.
