# Alert Logic ActiveIntegration Pack

This integration pack allows you to integrate with 
[Alert Logic](https://www.alertlogic.com/).

## Config

Request an API key from Alert Logic for your account. 
Copy the example configuration in [alertlogic.yaml.example](./alertlogic.yaml.example)
to `/opt/stackstorm/configs/alertlogic.yaml` and edit as required.

It should contain:

* ``apikey`` - Alert Logic API Key

You can also use dynamic values from the datastore. See the
[docs](https://docs.stackstorm.com/reference/pack_configs.html) for more info.


## Actions

* alertlogic.scan_get_results_by_title: Get the scan results for the latest complete execution
* alertlogic.scan_get_results: Get results of a scan execution.
* alertlogic.scan_list_scan_executions: Get a list of executions for given scan.
* alertlogic.scan_list_scans: Get a list of scans for a customer.

## Aliases

* list_scan_executions
* get_scan_results
* list_scans
