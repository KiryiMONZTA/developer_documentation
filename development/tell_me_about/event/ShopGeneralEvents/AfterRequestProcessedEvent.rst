AfterRequestProcessedEvent
===========================

Namespace:

.. code-block:: php

    OxidEsales\EshopCommunity\Internal\Transition\ShopEvents\AfterRequestProcessedEvent

This event will be dispatched by shop to inform services that a request has been processed.

Usage example: reverse proxy (varnish) can use this event to execute cache before shop redirects.
