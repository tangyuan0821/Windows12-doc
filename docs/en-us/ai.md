---
layout: default
nav_order: 4
lang: en-us
permalink: /e-us/ai/
---

This AI and documentation are from github@NB-Group
# AI Copilot Backend Introduction
## Introduction
AI Copilot is an AI-based text generation tool that uses the LLAMA model and can automatically generate text content.
This AI is deployed on the Worker AI service provided by the Cloudflare platform, which can receive requests from frontend pages and return the generated text.

However, the AI service currently deployed by Cloudflare is subject to restrictions and cannot be accessed directly, so a VPN is required to access it.
I have deployed a forwarding program on pythonanywhere to forward requests to Cloudflare.

The specific code for the Cloudflare AI server can be viewed [here](https://github.com/tjy-gitnub/win12/blob/main/scripts/AI%20Copilot%20service/Cloudflare%20AI.js)
