| [Home](../README.md) |
|----------------------|

# Contents

The **SOC Utilities** solution pack contains the following resources:

## Playbook Collection

| 06 - IRP - Reporting |
|----------------------|

| # | Playbook Name | Description                                    |
|---|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| 1 | Export Selected Records                | Exports all selected records to a JSON file and creates an attachment record for the same.                              |
| 2 | Import Data                            | Imports a valid JSON file to a relevant module and creates subsequent records.                                          |

|08 - SOC Utilities |
|:---------------------------------------------|

| # | Playbook Name                                        | Description                                                                                                                     |
|:----:|:-----------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------|
| 1    | Clone FortiSOAR Module                               | Playbook allows to clone a FortiSOAR module.                                                                                     |
| 2    | Terminate Pending Manual Inputs                      | Terminates all manual input pending for user action/inputs that have been created before the specified timestamp.                |
| 3    | Terminate Awaiting Data Ingestion playbooks          | Terminates data ingestion playbooks which are stuck in awaiting state till last x minutes                                        |
| 4    | Extract Related Alert of Pending Manual Input in CSV | Retrieve all pending manual input alert records for user action/input and generates CSV attachments for related and missing alerts.|

| 08 - Utilities |
|----------------|


| #  | Playbook Name                                                                      | Description                                                                                                                                                       |
|----|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | Activate Inactive Users                                                            | Find the Inactive users and activate them                                                                                                                         |
| 2  | Activate inactive users - Update user status                                       | This is a subroutine playbook to update the user status as active                                                                                                 |

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|----------------------------------------------|------------------------------------------------|--------------------------|