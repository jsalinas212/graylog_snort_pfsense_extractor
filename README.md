# Graylog Extractor for Snort on pfSense

## Description
Snort field extraction from pfSense sys logs for parsing in Graylog. This is only for IDS detections and not other general snort logs.

![Graylog Example Image](./img/example.png)

## Requirements
N/A

## Usage
- Step 1: Navigate to System > Inputs.

![Step 1](./img/step1.png)
- Step 2: Click on Manage Extractors for the input you want to work with.

![Step 2](./img/step2.png)
- Step 3: Clicl Actions > Import Extractors.

![Step 3](./img/step3.png)
- Step 4: Paste in JSON and click Add Extractors to Input.

![Step 4](./img/step4.png)

It should show that it completed successfully and the new extractors should now be available.

![Last](./img/last.png)

## Author
* JA Salinas
