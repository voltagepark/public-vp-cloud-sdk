# SlurmParameters

Configuration parameters for SLURM addon

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ssh_keys** | [**List[SlurmParametersSshKeysInner]**](SlurmParametersSshKeysInner.md) | SSH user configurations with multiple keys per user | 
**external_storage** | [**ExternalStorageConfig**](ExternalStorageConfig.md) |  | 

## Example

```python
from vpcloud_client.models.slurm_parameters import SlurmParameters

# TODO update the JSON string below
json = "{}"
# create an instance of SlurmParameters from a JSON string
slurm_parameters_instance = SlurmParameters.from_json(json)
# print the JSON string representation of the object
print(SlurmParameters.to_json())

# convert the object into a dict
slurm_parameters_dict = slurm_parameters_instance.to_dict()
# create an instance of SlurmParameters from a dict
slurm_parameters_from_dict = SlurmParameters.from_dict(slurm_parameters_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


