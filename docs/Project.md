# Project

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Synonyms** | Pointer to **[]string** |  | [optional] 
**Location** | Pointer to **string** |  | [optional] 
**Geolocation** | Pointer to [**Geolocation**](Geolocation.md) |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**External** | Pointer to **bool** | true if project was done outside of the organization | [optional] [default to false]
**ErpIds** | Pointer to **[]string** | IDs in the ERP system | [optional] 
**ProjectType** | Pointer to [**ProjectType**](ProjectType.md) |  | [optional] 
**Confidentiality** | Pointer to [**Confidentiality**](Confidentiality.md) |  | [optional] 
**Website** | Pointer to **NullableString** | Project website URL | [optional] 
**Github** | Pointer to **NullableString** | GitHub repository or profile URL/handle | [optional] 
**SocialMedia** | Pointer to **NullableString** | Social media profile URL or handle, for example X/Twitter | [optional] 

## Methods

### NewProject

`func NewProject() *Project`

NewProject instantiates a new Project object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectWithDefaults

`func NewProjectWithDefaults() *Project`

NewProjectWithDefaults instantiates a new Project object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSynonyms

`func (o *Project) GetSynonyms() []string`

GetSynonyms returns the Synonyms field if non-nil, zero value otherwise.

### GetSynonymsOk

`func (o *Project) GetSynonymsOk() (*[]string, bool)`

GetSynonymsOk returns a tuple with the Synonyms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSynonyms

`func (o *Project) SetSynonyms(v []string)`

SetSynonyms sets Synonyms field to given value.

### HasSynonyms

`func (o *Project) HasSynonyms() bool`

HasSynonyms returns a boolean if a field has been set.

### GetLocation

`func (o *Project) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *Project) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *Project) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *Project) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetGeolocation

`func (o *Project) GetGeolocation() Geolocation`

GetGeolocation returns the Geolocation field if non-nil, zero value otherwise.

### GetGeolocationOk

`func (o *Project) GetGeolocationOk() (*Geolocation, bool)`

GetGeolocationOk returns a tuple with the Geolocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeolocation

`func (o *Project) SetGeolocation(v Geolocation)`

SetGeolocation sets Geolocation field to given value.

### HasGeolocation

`func (o *Project) HasGeolocation() bool`

HasGeolocation returns a boolean if a field has been set.

### GetDescription

`func (o *Project) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Project) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Project) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Project) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetExternal

`func (o *Project) GetExternal() bool`

GetExternal returns the External field if non-nil, zero value otherwise.

### GetExternalOk

`func (o *Project) GetExternalOk() (*bool, bool)`

GetExternalOk returns a tuple with the External field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternal

`func (o *Project) SetExternal(v bool)`

SetExternal sets External field to given value.

### HasExternal

`func (o *Project) HasExternal() bool`

HasExternal returns a boolean if a field has been set.

### GetErpIds

`func (o *Project) GetErpIds() []string`

GetErpIds returns the ErpIds field if non-nil, zero value otherwise.

### GetErpIdsOk

`func (o *Project) GetErpIdsOk() (*[]string, bool)`

GetErpIdsOk returns a tuple with the ErpIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErpIds

`func (o *Project) SetErpIds(v []string)`

SetErpIds sets ErpIds field to given value.

### HasErpIds

`func (o *Project) HasErpIds() bool`

HasErpIds returns a boolean if a field has been set.

### GetProjectType

`func (o *Project) GetProjectType() ProjectType`

GetProjectType returns the ProjectType field if non-nil, zero value otherwise.

### GetProjectTypeOk

`func (o *Project) GetProjectTypeOk() (*ProjectType, bool)`

GetProjectTypeOk returns a tuple with the ProjectType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectType

`func (o *Project) SetProjectType(v ProjectType)`

SetProjectType sets ProjectType field to given value.

### HasProjectType

`func (o *Project) HasProjectType() bool`

HasProjectType returns a boolean if a field has been set.

### GetConfidentiality

`func (o *Project) GetConfidentiality() Confidentiality`

GetConfidentiality returns the Confidentiality field if non-nil, zero value otherwise.

### GetConfidentialityOk

`func (o *Project) GetConfidentialityOk() (*Confidentiality, bool)`

GetConfidentialityOk returns a tuple with the Confidentiality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidentiality

`func (o *Project) SetConfidentiality(v Confidentiality)`

SetConfidentiality sets Confidentiality field to given value.

### HasConfidentiality

`func (o *Project) HasConfidentiality() bool`

HasConfidentiality returns a boolean if a field has been set.

### GetWebsite

`func (o *Project) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *Project) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *Project) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *Project) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.

### SetWebsiteNil

`func (o *Project) SetWebsiteNil(b bool)`

 SetWebsiteNil sets the value for Website to be an explicit nil

### UnsetWebsite
`func (o *Project) UnsetWebsite()`

UnsetWebsite ensures that no value is present for Website, not even an explicit nil
### GetGithub

`func (o *Project) GetGithub() string`

GetGithub returns the Github field if non-nil, zero value otherwise.

### GetGithubOk

`func (o *Project) GetGithubOk() (*string, bool)`

GetGithubOk returns a tuple with the Github field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithub

`func (o *Project) SetGithub(v string)`

SetGithub sets Github field to given value.

### HasGithub

`func (o *Project) HasGithub() bool`

HasGithub returns a boolean if a field has been set.

### SetGithubNil

`func (o *Project) SetGithubNil(b bool)`

 SetGithubNil sets the value for Github to be an explicit nil

### UnsetGithub
`func (o *Project) UnsetGithub()`

UnsetGithub ensures that no value is present for Github, not even an explicit nil
### GetSocialMedia

`func (o *Project) GetSocialMedia() string`

GetSocialMedia returns the SocialMedia field if non-nil, zero value otherwise.

### GetSocialMediaOk

`func (o *Project) GetSocialMediaOk() (*string, bool)`

GetSocialMediaOk returns a tuple with the SocialMedia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialMedia

`func (o *Project) SetSocialMedia(v string)`

SetSocialMedia sets SocialMedia field to given value.

### HasSocialMedia

`func (o *Project) HasSocialMedia() bool`

HasSocialMedia returns a boolean if a field has been set.

### SetSocialMediaNil

`func (o *Project) SetSocialMediaNil(b bool)`

 SetSocialMediaNil sets the value for SocialMedia to be an explicit nil

### UnsetSocialMedia
`func (o *Project) UnsetSocialMedia()`

UnsetSocialMedia ensures that no value is present for SocialMedia, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


