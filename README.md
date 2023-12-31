# AWS Script Repository

## Overview
This repository contains a collection of Python scripts designed to manage various AWS resources. These scripts are aimed at automating tasks such as deleting ECS clusters, task definitions, security groups, and more.

## Scripts in the Repository
- `delete_ecs_clusters.py` - Script to delete ECS clusters.
- `delete_inactive_task_definitions.py` - Script to delete inactive ECS task definitions.
- `delete_security_groups.py` - Script to delete AWS security groups.
- `delete_task_definitions.py` - Script to delete ECS task definitions.
- `delete_task_revision.py` - Script to delete specific revisions of an ECS task.

## Prerequisites
- Python 3.x
- AWS CLI installed and configured with appropriate permissions.
- Necessary Python packages, e.g., `boto3`.

## Usage
Each script can be executed individually to perform its specific task. Ensure that you have the necessary AWS permissions set up before running these scripts.

### Example
```bash
python delete_ecs_clusters.py
```

## Contributing
If you would like to contribute to this repository, please fork it, make your changes, and submit a pull request. Your contributions are much appreciated!

## Disclaimer
Please use these scripts with caution. They can make irreversible changes to your AWS resources, and it's recommended to use them in a test environment before applying them in production.

## Contact
For any questions or suggestions regarding these scripts, please feel free to reach out to me at abdul.aziz.mohammed@outlook.com.
