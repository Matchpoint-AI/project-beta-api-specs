# Project Beta API Specifications

This repository contains the public OpenAPI specifications for the Project Beta API.

## Purpose

This repository provides public access to OpenAPI specifications while keeping the main API implementation private. This follows industry best practices for API-first development where the API contract (specification) is publicly accessible to consumers while the implementation details remain private.

## Structure

- `openapi.json` - Current OpenAPI 3.0 specification
- Tags correspond to releases in the main `project-beta-api` repository

## Usage

Frontend applications and API consumers can fetch the OpenAPI specification directly from this repository:

```bash
# Fetch latest spec
curl https://raw.githubusercontent.com/Matchpoint-AI/project-beta-api-specs/main/openapi.json

# Fetch specific version
curl https://raw.githubusercontent.com/Matchpoint-AI/project-beta-api-specs/v0.0.124/openapi.json
```

## Version Alignment

Each commit and tag in this repository corresponds to a specific commit in the private `project-beta-api` repository, ensuring complete traceability and version alignment.

## Maintenance

This repository is automatically updated by the CI/CD pipeline of the main API repository. Manual updates should not be necessary under normal circumstances.