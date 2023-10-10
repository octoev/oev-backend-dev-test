# Backend technical task

Welcome to Octopus Electric Vehicle's technical task for the Backend Developer role. For this task you will create a small backend service which ingests data and provides a simple interface to query it.

## Background

Across our various leasing products we use 'ratebooks' which list the rentals for specific car specification, term and mileage combinations (e.g. Tesla Model 3 Performance over 24 months and 10,000 miles). We may also have different funders providing different rentals. The `rates.csv` file provides a sample dataset with a few car specifications.

## Task

- Create a backend service that can ingest the dataset provided and store the results in a database
- Expose an API endpoint to fetch the cheapest rentals for a given car specification

## Requirements

- How the data is ingested is up to you (e.g. cli command/api request etc)
- The data model and database schema is also up to you
- Use a lightweight framework such as Flask or FastAPI
- Use SQLite or Postgres for the database
- Include a .git folder with the commit history for the project
- Include a README.md that explains how to setup and run the project and any assumptions you've made
- Once complete, create an archive of the project and send to the person that sent you this task

## Success criteria

- Correctness - does it meet the requirements and work as expected?
- Maintainability - is it easy for another developer to understand and expand on?
- Robustness - does it handle errors gracefully?

## Suggested time

We appreciate your time is valuable and we suggest you don't spend more than a couple of hours on this task. Please provide notes for anything else you would have done given more time.
