# CloudFuse

This repository is the root of CloudFuse.
CloudFuse is an online search engine that allows users to link Dropbox, Google Drive, and OneDrive accounts.
They can then search through the files of the linked cloud services.

---
## Installation

1. Clone this repo:
   ```bash
   git clone --recurse-submodules https://github.com/AAU-SW-P7/P7-Root.git
   cd P7-Root
   ```
2. Setup Docker container:
   ```bash
   docker compose -f compose.dev.yml up --force-recreate --build
   ```
---

## Usage

### Running CloudFuse

1. Make sure that your Docker containers are running.
2. Access localhost through your browser.
3. The CloudFuse login page should be shown. 
---
