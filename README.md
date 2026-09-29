# Introduction to Data Science · R Coursework

Early data-science exercises in **R**, including extracting product fields from HTML and serializing structured records to JSON.

这是早期的数据科学入门课程记录，保留原始练习、截图和报告。

## Repository guide

| File | Purpose |
| --- | --- |
| [Tutorial3.R](Tutorial3.R) | HTML parsing with `rvest` / `xml2`, string cleaning and JSON serialization |
| [Tutorial3.png](Tutorial3.png) | Original exercise screenshot |
| [Coursework report](Tutorial3_S2124920_Hang%20Gu%E2%80%94R.pdf) | Original tutorial report |
| [HelloWorld.md](HelloWorld.md) | Introductory Markdown exercise |

## Reading and running the exercise

The script imports `xml2`, `rvest`, `stringr` and `jsonlite`. Read it in an R editor to follow the extraction steps.

The exercise targets a historical product page with fixed CSS selectors. The live page may have changed, may block automated access, or may return missing fields; this is not a maintained scraper. The original script does not validate equal-length fields before creating the data frame. For a reproducible extension, use a permitted local HTML fixture and explicit missing-field handling.

## Related work

- [Frontend & Data Lab](https://github.com/GuHang2011/frontend-data-lab): a new synthetic-data pipeline, dashboard and practical notes.
- [Academic portfolio](https://guhang2011.github.io/): current research interests and engineering experience.
