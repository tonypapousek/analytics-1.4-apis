# SaveEVars

Updates the commerce variables \(eVars\) for the requested report suites.

## ReportSuite.SaveEVars parameters

|Name|Type|Description|
|----|----|-----------|
|**rsid\_list** |`array(xsd:string)` |A list of report suite IDs.|
|**evars** |`tns:evar` |List of eVars for the specified report suites, including the settings for each eVar.|

## ReportSuite.SaveEVars response

|Type|Description|
|----|-----------|
|`xsd:int` |Returns `1` if the operation is successful. Otherwise, returns `0`.|

**Parent topic:** [Report Suite](../../methods/report_suite/c_api_admin_methods_repsuite.md)

