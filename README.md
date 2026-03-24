# Daily Breakdown Dashboard Data

## Resources

| Resource | Link |
|----------|------|
| Google Sheet | [Dashboard spreadsheet](https://docs.google.com/spreadsheets/d/1DFD_c2cp2FFvbYkDBUJC5TPbFEfcfuzzADP6TE6WpBc/edit?gid=1691174245#gid=1691174245) |
| Google Slides | [Presentation](https://docs.google.com/presentation/d/1u1yc3107L7P0QnqiVdNm_8BWzI_geoCNp_kY0Pjq8vE/edit?slide=id.g3da12f274fc_2_45#slide=id.g3da12f274fc_2_45) |

---

## Project overview

This document summarizes the data in the **Dashboard** sheet of the project spreadsheet. The sheet tracks and analyzes daily values (e.g. user activity, sales, or other metrics) broken down by time segments.

## Key data table (`A6:F26` sample)

The main table is a daily time series of the core metric.

### Columns

- **Date** — Day for which the metric is recorded.
- **Time buckets (Afternoon, Evening, Morning)** — Values for each segment of the day.
- **Grand total** — Sum of all time segments for that date.

## Dashboard parameters / filters (`A2:D4` sample)

A smaller table (around `A2:D4`) holds high-level filters or parameters that may drive a linked dashboard or report.
