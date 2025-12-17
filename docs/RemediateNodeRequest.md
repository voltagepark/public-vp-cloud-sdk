# RemediateNodeRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node_id** | **str** | Unique identifier for the node | 
**message** | **str** | Description of the remediation reason | 
**cause** | **str** | Cause for the remediation request | 

## Example

```python
from vpcloud_client.models.remediate_node_request import RemediateNodeRequest

# TODO update the JSON string below
json = "{}"
# create an instance of RemediateNodeRequest from a JSON string
remediate_node_request_instance = RemediateNodeRequest.from_json(json)
# print the JSON string representation of the object
print(RemediateNodeRequest.to_json())

# convert the object into a dict
remediate_node_request_dict = remediate_node_request_instance.to_dict()
# create an instance of RemediateNodeRequest from a dict
remediate_node_request_from_dict = RemediateNodeRequest.from_dict(remediate_node_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


