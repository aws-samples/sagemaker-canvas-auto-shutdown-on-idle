# 0.3 (2025-04-01)

- Minor update in a Lambda Function to correct the alarm action by setting the alarm state to "OK"
- Addition IAM permision to allow lambda to set Alarm State

# 0.2 (2024-05-15) - Minor Updates

Addressing Issues #1 and #2. 

- Fixed a minor bug with Lambda trying to delete apps already in Deleted status and failing
- Changed the hardcoded value of the GetMetricData StartTime

# 0.1 (2023-10-24) - Inital Release 

## Release Highlight

First version of the Canvas Auto-shutdown scripts. 

## Features 

- Auto-shutdown script for all users, in all domains, in one region
- Auto-shutdown script for all users, in one domain, in one region
- Auto-shutdown script for one user, in one domain, in one region
