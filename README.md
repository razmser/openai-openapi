# OpenAPI spec for the OpenAI API

Fork of https://github.com/openai/openai-openapi
All issues should be directed there.

## Purpose

This project maintains a daily-updated OpenAPI specification for the OpenAI API. A GitHub Actions workflow automatically fetches the latest spec from:
https://app.stainless.com/api/spec/documented/openai/openapi.documented.yml

The spec is saved locally as `openapi.yaml`, providing a git history of changes over time.

## Why Fork?

The official repository has a [`manual_spec`](https://github.com/openai/openai-openapi/tree/manual_spec) branch, but it does not appear to be updated regularly.
