# JSON Basics

## Overview
JSON is a common data format for APIs and configs.

## Example
```json
{
  "name": "app",
  "port": 8080
}
```

## Important commands
- `jq '.' file.json` use: pretty print JSON
- `jq '.name' file.json` use: read a field value

## Interview questions with answers
- Q: What is JSON used for?
  A: Data exchange in APIs and configuration files.
- Q: How is JSON different from YAML?
  A: JSON is strict and uses braces; YAML is more human-friendly.
