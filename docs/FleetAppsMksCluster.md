# FleetAppsMksCluster

MK8s (managed Kubernetes) cluster information for this fleet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cluster_id** | **str** | MK8s cluster ID | 
**cluster_name** | **str** | MK8s cluster name | 
**installation_status** | **str** | MK8s installation status on the fleet | 
**cluster_status** | **str** | Current MK8s cluster status | [optional] 
**kubeconfig** | **str** | The kubeconfig for accessing the cluster (if available) | [optional] 

## Example

```python
from vpcloud_client.models.fleet_apps_mks_cluster import FleetAppsMksCluster

# TODO update the JSON string below
json = "{}"
# create an instance of FleetAppsMksCluster from a JSON string
fleet_apps_mks_cluster_instance = FleetAppsMksCluster.from_json(json)
# print the JSON string representation of the object
print(FleetAppsMksCluster.to_json())

# convert the object into a dict
fleet_apps_mks_cluster_dict = fleet_apps_mks_cluster_instance.to_dict()
# create an instance of FleetAppsMksCluster from a dict
fleet_apps_mks_cluster_from_dict = FleetAppsMksCluster.from_dict(fleet_apps_mks_cluster_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


