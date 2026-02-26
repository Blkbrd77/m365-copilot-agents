# Export Guidance for Migration Context

To enable the Copilot agent to provide the best guidance, collect exports from all relevant systems:

## 1. Access Database

- Export Table structures (Fields, Data Types, Indexes)
- Export any relationships, queries, forms, and reports
- Save as XML or CSV (see: sample-access-export.xml)

## 2. Power Apps

- Export app definition as JSON (Solutions > Export)
- Include entity/config schema, forms, views (see: sample-powerapps-export.json)

## 3. Power Automate

- Export flow logic and steps per flow
- Save as JSON (Solutions > Export) (see: sample-automate-export.json)

## 4. Dataverse

- Export schema, roles, business rules
- Document API endpoints and connection settings (`configs/dataverse-connection.sample.json`)

## General Tips

- Store exported files in the `samples/` directory
- Make sure record counts, lookup fields, and relationships are defined
- If possible, include sample data to support agent reasoning
