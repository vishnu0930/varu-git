AWS Cloud Cost Optimization - Identifying Stale Resources

Description:
This lambda function will check all the stale EBS snapshots deletes them if it is attached to volume and that volume is not associated with any active instance also deletes the EBS snapshots which are not attached to any volumes
