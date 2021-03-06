Mordor Labs
===========

The mordor project provides pre-recorded datasets to the community to expedite the analytics validation process and allow hunters to learn more about adversarial techniques.
Each Mordor environment was designed to replicate a very small network with the essential devices to colllect information from adversarial activities.
The Blacksmith project maintains the design and code to deploy custom mordor network environments to simulate adversarial techniques and export all the data generated.

Mordor Shire
############

.. image:: _static/mordor-shire-network.png
    :alt: Erebor
    :scale: 30%

This mordor environment was designed to replicate a very small network with the essential devices to colllect information from adversarial activities.
This environment is a Windows environment with several Windows event providers enabled and Sysmon deployed.

.. toctree::
   :maxdepth: 2

   AWS <mordor_shire_aws>

Mordor Erebor
#############

.. image:: _static/mordor-erebor-network.png
    :alt: Erebor
    :scale: 30%

This mordor environment was designed to replicate a very small network with the essential devices to colllect information from adversarial activities.
This environment is a Windows environment with SilkETW running on every endpoints to collect ETW telemetry via the event log.

.. toctree::
   :maxdepth: 2

   AWS <mordor_erebor_aws>