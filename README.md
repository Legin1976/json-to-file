[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/devops-actions/json-to-file/badge)](https://api.securityscorecards.dev/projects/github.com/devops-actions/json-to-file)
[![build-test](https://github.com/devops-actions/json-to-file/actions/workflows/test.yml/badge.svg)](https://github.com/devops-actions/json-to-file/actions/workflows/test.yml)


# Purpose
Write JSON from to a file, without having to worry about string escaping on a bash script.

# Usage
``` yaml
- uses: devops-actions/json-to-file@v1.0.0
  with:
    json: '{"test": "test"}'
    filename: 'test.json'
```
