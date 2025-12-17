# Bootstrap


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloud_init** | **str** | Cloud-init script | [optional] 
**machine_image** | **str** | Machine image to use | 
**ssh_pub_keys** | **List[str]** | List of SSH public keys | 

## Example

```python
from vpcloud_client.models.bootstrap import Bootstrap

# TODO update the JSON string below
json = "{}"
# create an instance of Bootstrap from a JSON string
bootstrap_instance = Bootstrap.from_json(json)
# print the JSON string representation of the object
print(Bootstrap.to_json())

# convert the object into a dict
bootstrap_dict = bootstrap_instance.to_dict()
# create an instance of Bootstrap from a dict
bootstrap_from_dict = Bootstrap.from_dict(bootstrap_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


