---------------------------------
Omeka_Session_SaveHandler_DbTable
---------------------------------

.. php:class:: Omeka_Session_SaveHandler_DbTable

    Package: :doc:`Session </Reference/packages/Session/index>`

    Wrapper for Zend_Session_SaveHandler_DbTable to hard code the table 
    definition. This boosts performance by skipping the DESCRIBE query that 
    retrieves this metadata by default.
    
    Note that this must be updated meticulously after any changes to thesessions table schema.

    .. php:method:: init()