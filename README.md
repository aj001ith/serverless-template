curl -X POST "http://localhost:8000/" \
-H "Content-Type: application/json" \
-d \
'
{
    "apiKey": "YOUR_API_KEY",
    "modelKey": "YOUR_MODEL_KEY",
    "modelInputs": {"prompt": "Hello I am a [MASK] model."}
}'



































# 🍌 Banana Serverless

This repo gives a framework to serve ML models in production using simple HTTP servers.

# Quickstart
**[Follow the quickstart guide in Banana's documentation to use this repo](https://docs.banana.dev/banana-docs/quickstart).** 

*(choose "GitHub Repository" deployment method)*

<br>

# Helpful Links
Understand the 🍌 [Serverless framework](https://docs.banana.dev/banana-docs/core-concepts/inference-server/serverless-framework) and functionality of each file within it.

Generalize this framework to [deploy anything on Banana](https://docs.banana.dev/banana-docs/resources/how-to-serve-anything-on-banana).

<br>

## Use Banana for scale.
