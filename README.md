# Student Performance Analysis using Business Analytics

An interactive single-page dashboard that analyses student performance using the four stages of business analytics: descriptive, diagnostic, predictive and prescriptive.

## Features
- Department filter (CSE, ECE, MECH, CIVIL)
- Control panel: pass mark, at-risk score and attendance thresholds, attendance and study-hours improvement scenario
- Charts: grade distribution, attendance vs score with trend line, subject averages, factor correlations
- What-if predictor based on multiple linear regression
- Auto-generated insights and an at-risk student table with suggested actions

## Run locally
Open `index.html` in any browser. No installation or internet connection is needed.

## Data
The 160 student records are a synthetic sample generated in the script inside `index.html`. Replace the generator loop (`const D=[]; for(...)`) with your own records to analyse real data.

## Tech
HTML, CSS and vanilla JavaScript. No external libraries.
