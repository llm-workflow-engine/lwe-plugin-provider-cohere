# LLM Workflow Engine (LWE) Cohere Provider plugin

Cohere Provider plugin for [LLM Workflow Engine](https://github.com/llm-workflow-engine/llm-workflow-engine)

Access to [Cohere](https://docs.cohere.com/docs/models) models.

## Installation

### Export API key

Grab an Cohere API key from [https://dashboard.cohere.ai/api-keys](https://dashboard.cohere.ai/api-keys)

Export the key into your local environment:

```bash
export COHERE_API_KEY=<API_KEY>
```

### From packages

Install the latest version of this software directly from github with pip:

```bash
pip install git+https://github.com/llm-workflow-engine/lwe-plugin-provider-cohere
```

### From source (recommended for development)

Install the latest version of this software directly from git:

```bash
git clone https://github.com/llm-workflow-engine/lwe-plugin-provider-cohere.git
```

Install the development package:

```bash
cd llm-workflow-engine
pip install -e .
```

## Configuration

Add the following to `config.yaml` in your profile:

```yaml
plugins:
  enabled:
    - provider_cohere
    # Any other plugins you want enabled...
```

## Usage

From a running LWE shell:

```
/provider cohere
/model model base
```
