Hyperfoil shutdown runner
=========

Stops Hyperfoil instances. By default this waits until currently executed run finishes.

Role Variables
--------------

* `hyperfoil_shutdown_force` (optional): Terminate Hyperfoil controller even if there's an ongoing run.
* `hyperfoil_controller_group` (optional): Ansible group that hosts the controller. Default is `hyperofoil-controller`.
* `hyperfoil_controller_port` (optional): Port on which Hyperfoil should listen

License
-------

Apache License, Version 2.0