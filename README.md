# HP ZRT Support

HP Z Runtime (ZRT) is a CLI tool that wraps vLLM, providing a streamlined experience
for serving large language models. It handles environment setup, model
management, and inference serving with simple, intuitive commands.

This repository is the hub for bug reports and new feature requests. 

## Installing

```
snap install --classic zrt
```

## Get started in under 5 minutes

1. Setup Z Runtime:

       sudo zrt setup

2. Disable auth and TLS:

       zrt config set proxy.auth.type none && zrt config set proxy.tls.enabled false
   Note: This is safe with default (local) settings. Secure your public releases.

3. Download and serve a model:

       zrt serve nvidia/NVIDIA-Nemotron-3-Nano-4B-BF16
   → OpenAI-compatible API will be available at (by default) http://127.0.0.1:8080/v1/


## File a bug or feature request

Navigate to "Issues" and select the "New issue" button to file a bug report or a request for new functionality. Please use the defined templates so we receive helpful information about your bug or idea. We appreciate your input!

## Documentation

Learn more at https://zdocs.datascience.hp.com/docs/zruntime/overview
