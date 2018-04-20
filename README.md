# alfred-adapters
[Alfred 3][1] workflow for controlling various adapters.

## Installation

1) Install [alfred-adapters.][2]
2) All further updates are handled automatically.

## Usage

Workflow is simple and just toggles the adapter state from disabled to enabled and vice versa. Currently, Bluetooth and WiFi adapters could be controlled.

### Bluetooth Adapter

Type ```bt``` and workflow shows the current adapter state and shows you will happen if you continue.

![Alfred disabled bluetooth](doc/images/bt-disabled.png?raw=true "")
![Alfred enabled bluetooth](doc/images/bt-enabled.png?raw=true "")

### WiFi Adapter

Type ```wifi``` and workflow shows the current adapter state and shows you will happen if you continue. Default WiFi Apdapter Hardware Port is ```en0``` and could be adjusted in a workflow configuration - the ```wifi_hwport``` variable.


![Alfred disabled bluetooth](doc/images/wifi-disabled.png?raw=true "")

If WiFi is connected to an access-point, its name will be shown. 

![Alfred enabled bluetooth](doc/images/wifi-enabled.png?raw=true "")




[1]: https://www.alfredapp.com/
[2]: https://github.com/vookimedlo/alfred-adapters/releases/latest
