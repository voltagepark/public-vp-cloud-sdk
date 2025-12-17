# FleetApps

Fleet applications configuration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mk8s** | **str** | Enable or disable MK8s (managed Kubernetes) for this fleet | [optional] 
**slurm** | **str** | Enable or disable Slurm for this fleet | [optional] 
**mk8s_cluster** | [**FleetAppsMksCluster**](FleetAppsMksCluster.md) | MK8s cluster information (only present when mk8s is enabled) | [optional] 
**slurm_parameters** | [**SlurmParameters**](SlurmParameters.md) | Slurm configuration (only present when slurm is enabled) | [optional] 

## Example

```python
from vpcloud_client.models.fleet_apps import FleetApps

# TODO update the JSON string below
json = "{}"
# create an instance of FleetApps from a JSON string
fleet_apps_instance = FleetApps.from_json(json)
# print the JSON string representation of the object
print(FleetApps.to_json())

# convert the object into a dict
fleet_apps_dict = fleet_apps_instance.to_dict()
# create an instance of FleetApps from a dict
fleet_apps_from_dict = FleetApps.from_dict(fleet_apps_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


