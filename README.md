 # highcharts-with-google-sheets
sample Highcharts with data in published Google Sheets

## about Highcharts
http://www.highcharts.com - free for personal website, a school site, or non-profit organizations; commercial use requires a license

## Line chart
- demo https://jackdougherty.github.io/highcharts-with-google-sheets/line.html
- Google Sheet https://docs.google.com/spreadsheets/d/1eGnc81p7-Rn7O2LMcOfSIht-Z9NYU-KAi9vJPjf6SWA/edit#gid=0

## Scatter chart
- demo https://jackdougherty.github.io/highcharts-with-google-sheets/scatter.html
- Google Sheet https://docs.google.com/spreadsheets/d/1EfNavL8tH_M86V5FQCUfpuqkvd5WpzHZRH9bTywZHdM/edit#gid=0
- instructions:
  - in the first tab of a published Google Sheet, the first two columns may contain any labels, but layout must begin with numeric x, y data, then names, etc.
   - paste the googleSpreadsheetKey into the code, and modify other items mentioned in code comments

## Bubble chart
- demo https://jackdougherty.github.io/highcharts-with-google-sheets/bubble.html
- Google Sheet https://docs.google.com/spreadsheets/d/1fYJOd-2agLPg38qhblS8qoZGWGkKcK-3uTsMpf37Hys/edit#gid=0

- demo 3 https://jackdougherty.github.io/highcharts-with-google-sheets/bubble3.html
- Google Sheet https://docs.google.com/spreadsheets/d/1wh6nYrlou3VS2UMgP6wGrRl-bkB2UpY_g3gxqYYkgVw/edit#gid=0

- instructions:
 - in the first tab of a published Google Sheet, the first three columns must be labeled x, y, z and contain numeric data, followed by any additional columns
 - paste the googleSpreadsheetKey into the code, and modify other items mentioned in code comments
 - bubble size is automatically determined by the data range in column z
 - the only way to make the bubbles semi-transparent is specify the colors in rgba() model. fillOpacity does not work and nothing else works

## Credits
- Thanks @ilyankou for seriesMapping data from Google Sheets, tooltips, and improving overall code
- Thanks @andrewbtran at http://TrendCT.org for function to display financial data (with $ and commas)

## Code resources
- http://www.highcharts.com/docs/working-with-data/data-module
- http://www.highcharts.com/cloud/import-data/how-to-set-up-a-google-spreadsheet-file

- http://www.highcharts.com/demo/scatter
- http://jsfiddle.net/gh/get/jquery/1.7.2/highslide-software/highcharts.com/tree/master/samples/highcharts/data/google-spreadsheet/
