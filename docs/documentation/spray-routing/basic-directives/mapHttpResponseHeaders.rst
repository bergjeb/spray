.. _-mapHttpResponseHeaders-:

mapHttpResponseHeaders
======================

Changes the list fo response headers that was generated by the inner route.

Signature
---------

.. includecode:: /../spray-routing/src/main/scala/spray/routing/directives/BasicDirectives.scala
   :snippet: mapHttpResponseHeaders

Description
-----------

The ``mapHttpResponseHeaders`` directive is used as a building block for :ref:`Custom Directives` to transform the list of
response headers that was generated by the inner route.

See :ref:`Response Transforming Directives` for similar directives.

Example
-------

.. includecode:: ../code/docs/directives/BasicDirectivesExamplesSpec.scala
   :snippet: mapHttpResponseHeaders
