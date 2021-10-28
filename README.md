# ps_powerbi_to_json

## How it works
It parses Power Query queries, their names, Power Query Editor groups, and some additional properties from a PBIT file. Then it transforms all the parsed information into a form which is used by Power BI Dataflows. It is a JSON file used for import/export of dataflows.

## How to use it
1. Export an PBIX file as PBIT
2. Modifiy the value of $filename line 322 to match with your PBIT
3. Run the powershell and get your generated JSON 
4. Import the JSON as Dataflow in Power BI Service

## Ideas / Fix
Change $filename as run parameter

Credits to Michal Dvorak (@nolockcz) for original idea
