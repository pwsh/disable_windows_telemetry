# disable_windows_telemetry
XML and Registry and GPO exports to disable various Windows Telemetry Items

Future work will include using the actual GPO items from https://learn.microsoft.com/en-us/mem/configmgr/desktop-analytics/group-policy-settings

The XML files can by copied and pasted into a GPO under the registry settings, 
1. just copy the content to a clipboard
2. Navigate to either the user or machine GPO settings depending on the file content
3. select the registry under preferences > control panel settings > registry
4. right click registry and choose paste
5. the settings should automatically be created
