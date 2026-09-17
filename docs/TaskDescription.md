# TaskDescription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskDescription** | **string** |  | 
**TaskType** | [**AvailabilityType**](AvailabilityType.md) |  | 

## Methods

### NewTaskDescription

`func NewTaskDescription(taskDescription string, taskType AvailabilityType, ) *TaskDescription`

NewTaskDescription instantiates a new TaskDescription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskDescriptionWithDefaults

`func NewTaskDescriptionWithDefaults() *TaskDescription`

NewTaskDescriptionWithDefaults instantiates a new TaskDescription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskDescription

`func (o *TaskDescription) GetTaskDescription() string`

GetTaskDescription returns the TaskDescription field if non-nil, zero value otherwise.

### GetTaskDescriptionOk

`func (o *TaskDescription) GetTaskDescriptionOk() (*string, bool)`

GetTaskDescriptionOk returns a tuple with the TaskDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskDescription

`func (o *TaskDescription) SetTaskDescription(v string)`

SetTaskDescription sets TaskDescription field to given value.


### GetTaskType

`func (o *TaskDescription) GetTaskType() AvailabilityType`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *TaskDescription) GetTaskTypeOk() (*AvailabilityType, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *TaskDescription) SetTaskType(v AvailabilityType)`

SetTaskType sets TaskType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


