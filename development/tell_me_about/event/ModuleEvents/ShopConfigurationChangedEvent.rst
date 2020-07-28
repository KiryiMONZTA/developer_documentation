ShopConfigurationChangedEvent
=============================

Namespace:

.. code-block:: php

    OxidEsales\EshopCommunity\Internal\Framework\Config\Event\ShopConfigurationChangedEvent

This event will be triggered when shop configuration was changed in database.

Usage example: reverse proxy (varnish) can use this event to invalidate parts of cache depending on places
affected by configuration change.
