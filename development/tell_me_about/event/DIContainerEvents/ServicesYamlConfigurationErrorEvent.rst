ServicesYamlConfigurationErrorEvent
===================================

Namespace:

.. code-block:: php

	OxidEsales\EshopCommunity\Internal\Framework\Module\Setup\Event\ServicesYamlConfigurationErrorEvent;

This event will be dispatched when there are classes referenced in a `services.yaml` file of a module
that are not loadable.

Usage example: The EventLoggingSubscriber writes this error to the log file.
