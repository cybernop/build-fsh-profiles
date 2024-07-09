# github Action "build-fsh-profiles"

This github action builds FHIR profiles using FSH Sushi and Firely Terminal. The Firely Terminal is used to download and inflate the project dependencies before building the JSON files using FSH Sushi.

## Parameters

### Input

| Name | Description | Required | Default |
| --- | --- | :-: | :-: |
| `project-dir` | Root directory of the FSH Sushi project | False | `.` |
| `sushi-version` | Version of FSH sushi for building | True | - |
| `firely-terminal-version` | Version of Firely Terminal | True | - |
| `node-version` | Version of NodeJS | False | `tls/*` |
| `dotnet-version` | Version of .NET | False | `6.0.x` |
