# JobCompass Personal

A personal job-search and application-preparation system built with n8n, Google Gemini, Google Sheets and a web interface.

JobCompass brings relevant vacancies, an accurate master CV and application-document preparation into one organised process.

[Explore the public home page](https://jobcompass.blackberet2.chatgpt.site)

The live personal workspace is restricted to its owner. Public visitors can explore the home page and product information.

## What it does

- Searches supported job sources on a configured weekday schedule.
- Assesses vacancies against the candidate profile.
- Filters unsuitable records and removes duplicates.
- Saves shortlisted jobs and sends email updates.
- Imports readable CV text or assembles a CV through guided questions.
- Supports editing, saving and factual confirmation of the master CV.
- Prepares tailored CV, cover-letter and human-review-checklist PDFs.
- Accepts a manually pasted advert when automatic extraction fails.
- Displays preparation status, document links and recorded search activity.
- Lets the user manually record application progress.

## How it works

1. Build or import a master CV.
2. Review and confirm its factual accuracy.
3. Review shortlisted vacancies and advisory match assessments.
4. Request application drafts.
5. Review the three documents.
6. Open the original advert and apply directly.
7. Record application progress.

JobCompass does not submit applications automatically or guarantee employment.

## Technology

- **n8n:** workflow orchestration, scheduling and integrations.
- **Google Gemini:** job assessment and application drafting.
- **Google Sheets:** job tracking and search-activity records.
- **Google Drive:** generated document storage.
- **Web interface:** CV management, shortlist review, document access and progress tracking.

## Lessons learned

A successful workflow execution does not necessarily produce new jobs. Users still need a clear explanation of the outcome.

This led to separate reporting for new matches, no suitable matches, duplicate-check outcomes and failures.

Other improvements included correcting assessment parsing, broadening keyword coverage and adding a saved-advert fallback for unsupported extraction sources.

## Current scope

The personal version focuses on Abuja opportunities and remote roles assessed as accepting Nigeria-based applicants.

The published weekday schedule and newly connected activity-writing paths are awaiting observation during normal scheduled use.

## Limitations and future work

- AI assessments and documents require human review.
- Vacancy availability and employer requirements must be verified.
- Dashboard search settings are currently read-only.
- Private multi-user accounts and an interactive AI assistant are future capabilities.

## Repository status

This repository currently documents the project. Sanitised workflow exports, source code and setup instructions will be added separately.

Personal CVs, tracker records, credentials, private document links and execution data must not be included.
