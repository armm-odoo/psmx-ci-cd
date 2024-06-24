# PSMX CI / CD Automations
This repo contains all the Github Workflows used in PSMX Repos. 

## Contributing
NOTE: All repos read from the `master` branch. Avoid modifying it directly. Instead, 
1. Create your own branch
2. Create a test repo inside of `odoo-ps` Organization
3. Make your changes. Make sure to update the branch name when necessary (e.g., for downloading config files from this repo)
4. Inside the new repo, test the workflows following [these instructions](https://docs.github.com/en/actions/using-workflows/reusing-workflows#calling-a-reusable-workflow)

## Configuration Files
Some workflows require configuration files. For better scalability, these should live inside this repo, and should be downloaded in their respective workflow via `wget`.
