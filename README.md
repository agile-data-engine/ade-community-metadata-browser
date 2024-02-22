# ade-community-metadata-browser
ADE Community solution to export metadata from Metadata Interface and query it with DuckDB

## Pre-requisites
- ADE External API CLI installed & access keys set up for one tenant
    - https://github.com/solita/ade-external-api-cli
    - CLI needs to work to be able to run the notebook
- Python libraries installed as specified in requirements.txt

## Running in virtualenv
To run notebook in virtualenv:
```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Notes
When you run the script to a large environment, it can take up to 30 minutes to fetch all data. Also it is recommended to first run this against development environment to see how it performs.

## Disclaimer

**The repository is provided as community solution and it may require modifications to fit your use case. Note that this solution is not part of the Agile Data Engine product. Please use at your own caution.**