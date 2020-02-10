# csv-to-googlespreadsheet

This is a simple Node.js script that download a csv and export it to google spreadsheet.

## Environment Variables


- `CREDENTIAL_JSON`: the credential jsons in one line string
- `SPREADSHEET_ID`: your google spreadsheet id
- `REMOTE_CSV_PATH`: remote csv path. e.g. `http://www.chp.gov.hk/files/misc/hk_confirmed_cases_epi_curve_chi.csv`
- `GOOGLE_APPLICATION_CREDENTIALS`: the path for saving 

## Before you start

- Make sure you created a service account that enabled Drive API.
- Make sure the google spreadsheet invite that service account's email and allow edit
- Name your sheet `master`
