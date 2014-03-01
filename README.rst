###################
low_battery_suspend
###################

Simple bash script to suspend the system based on the output of ``acpi``.
Assumes ``systemctl suspend``.

.. code:: bash

  Usage: low_battery_suspend [1-100]

    Takes a percentage which is compared against the actual battery percentage.
    If the actual battery percentage <= provided percentage, then suspend the system.
