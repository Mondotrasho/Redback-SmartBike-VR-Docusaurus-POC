# Redback SmartBike VR - Docusaurus POC

Proof of concept for importing generated Unity API documentation into a Docusaurus documentation site.

This repository tests the receiving side of the SmartBike VR documentation pipeline. Generated Markdown is read from the companion DocFX POC and imported under `docs/unity-api`.

## Local test

Install the recorded dependencies and build the site:

```powershell
npm ci
npm run build
