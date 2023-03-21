# fast-scan-github-action
This repo contains a sample Github Action for running CAST Fast Scan on your repositories. The CAST Fast Scan performs an in depth scan of the source code identifying and segregating the technologies, languages and frameworks used. It also provides details of files like LoC, file size and file count for each identified language.
The result of the CAST Fast Scan is viewed through CAST Quick Assessment. The CAST Quick Assessment offers a simple but detailed presentation of the CAST Fast Scan result.

# Steps to run:
1. Add the CASTFastScan.yaml file in your repository under /.github/workflows directory.
2. And that's it:exclamation::sunglasses:

# Summary
Every time a commit is made to the main branch, the Github Action for CAST Fast Scan will be automatically triggered.The link to CAST Quick Assessment will be available in the summary of CAST-Fast-Scan job.
