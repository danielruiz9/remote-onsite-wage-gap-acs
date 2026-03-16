# Remote vs On-Site Wage Differences Using ACS 2022

## Overview
This project examines whether U.S. workers who report working from home earn different hourly wages than workers who work on-site, and how much of that difference can be explained by observable worker and job characteristics.

Using 2022 American Community Survey (ACS) microdata, the analysis constructs hourly wages from annual earnings, weeks worked, and usual weekly hours, and defines a remote-work indicator from the ACS “worked at home” commute response.

This project was completed as a **two-person ECO375 econometrics term project** at the University of Toronto.

## Research Question
Do remote workers earn different hourly wages than on-site workers, and how much of any observed gap remains after controlling for demographics, education, geography, and industry?

## Data
- 2022 American Community Survey (ACS) microdata
- Sample restricted to full-time wage and salary workers with positive earnings, weeks worked, and hours worked
- Hourly wages trimmed at the 1st and 99th percentiles in the final specification

## Methods
- Constructed hourly wage and log hourly wage measures
- Created a binary remote-work indicator from ACS commute data
- Estimated OLS regressions in Stata
- Added demographic and education controls
- Added state fixed effects and industry fixed effects
- Used robust standard errors throughout

## Main Finding
In a simple regression, remote workers appear to earn substantially more per hour than on-site workers. This raw gap shrinks meaningfully after adding controls and fixed effects. In the richest specification, the remaining remote wage premium is about 11%, suggesting that much of the raw difference reflects worker and job composition rather than a pure remote-work effect.

## Files
- `Observing Differences in Remote Work vs In Person Hourly Wages.pdf` — final report
- `Dofile 375 project FINAL.pdf` — exported Stata do-file / analysis workflow

## Collaboration Note
This repository contains materials from a collaborative two-person course project. It is shared here for portfolio purposes.

## Notes
The raw ACS data are not included in this repository. This repository is intended to document the research question, empirical approach, and project outputs.
