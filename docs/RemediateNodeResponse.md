# RemediateNodeResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node_id** | **str** | Unique identifier for the node | 
**remediate_status** | **str** | Status of the remediation request | 
**rejection_cause** | **str** | Reason for rejection if remediation was rejected, null if accepted | [optional] 

## Example

```python
from vpcloud_client.models.remediate_node_response import RemediateNodeResponse

# TODO update the JSON string below
json = "{}"
# create an instance of RemediateNodeResponse from a JSON string
remediate_node_response_instance = RemediateNodeResponse.from_json(json)
# print the JSON string representation of the object
print(RemediateNodeResponse.to_json())

# convert the object into a dict
remediate_node_response_dict = remediate_node_response_instance.to_dict()
# create an instance of RemediateNodeResponse from a dict
remediate_node_response_from_dict = RemediateNodeResponse.from_dict(remediate_node_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


