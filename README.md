# RHTools
Remote Hardware Tools [RHTOOLS v0.004a]

## Eclipse Plugin
The RH Tools Eclipse Plugin adds different functions to the Eclipse IDE to
interact with a remote hardware device, like a raspberry pi.

### Install
The Plugin should be installed via 
Help --> Install New Software 

The following updatesite should be used.
Eclipse Plugin updatesite
http://rhtools.digitizee.com/updatesite/

### Use
The plugin can be used via two icons, a menu or shortkeys.

#### Menu and Icons
* The left icon (see red rectangle) is used to run RH Tools like it is configured.
* The right icon is used to configure RH Tools.

#### Shortkeys
* Run RH Tools: Ctrl + 6
* Open Configurations: Ctrl + 7

#### Configuration
The configurations must be edited for the remote hardware. The checkboxes are
used to define if a specific task is done while running RHTools or not.

#### Run RHTools 
Running RHTools means that up to four tasks (as configured in the configurations)
are done automatically and step by step.

#### Other Functions
Other functions, like shutting down the device can be used via the menu.

#### Custom Command
The custom command menu-entry opens a dialog in which a custom command can be
entered which then will be operated on the remote hardware device.

#### Console 
A Console shows outputs of the plugin.

#### Progress Bar
A progress bar shows if the RH Tools currently runs a command.

## Shell-Scripts
The basic shell scipts can be used with unix terminal.
### Use
`./srciptname.sh config-name.cfg` 
