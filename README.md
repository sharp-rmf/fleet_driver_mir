# fleet_driver_mir
## Requirements

This fleet driver requires the following packages

|Packages|
|---|
|[Mir100-client](https://github.com/osrf/mir100-client)|
|[rmf_core](https://github.com/osrf/rmf_core)|

## Instructions 

The fleet driver subscribes to ros topics using the message types:
`ModeRequest.msg`
`PathRequest.msg`

and gives commands to the mir fleet.

Each mir requires login details that are to be described in a json.


To run the fleet driver, use the following command:

`ros2 run fleet_driver_mir fleet_driver_mir <CONFIG_FILE>.json`

sample format is provided in 'sample_config.json'

