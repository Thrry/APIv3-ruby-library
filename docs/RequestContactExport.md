# SibApiV3Sdk::RequestContactExport

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**export_attributes** | **Array&lt;String&gt;** | List of all the attributes that you want to export. These attributes must be present in your contact database. For example, [&#39;fname&#39;, &#39;lname&#39;, &#39;email&#39;]. | [optional] 
**contact_filter** | **Object** | This attribute has been deprecated and will be removed by January 1st, 2021. Only one of the two filter options (contactFilter or customContactFilter) can be passed in the request. Set the filter for the contacts to be exported. For example, {&#39;blacklisted&#39;:true} will export all the blacklisted contacts.  | [optional] 
**custom_contact_filter** | [**RequestContactExportCustomContactFilter**](RequestContactExportCustomContactFilter.md) |  | [optional] 
**notify_url** | **String** | Webhook that will be called once the export process is finished | [optional] 


