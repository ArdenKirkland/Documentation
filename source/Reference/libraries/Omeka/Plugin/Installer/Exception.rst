--------------------------------
Omeka_Plugin_Installer_Exception
--------------------------------

.. php:class:: Omeka_Plugin_Installer_Exception

    An exception thrown when the plugin installer is unable to 
    install, uninstall, activate, deactivate, or upgrade a plugin.

    .. php:attr:: message
    


    .. php:attr:: string
    


    .. php:attr:: code
    


    .. php:attr:: file
    


    .. php:attr:: line
    


    .. php:attr:: trace
    


    .. php:attr:: previous
    


    .. php:method:: __clone()

    .. php:method:: __construct($message, $code, $previous)
    
        :param unknown $message: 
        :param unknown $code: 
        :param unknown $previous:

    .. php:method:: getMessage()

    .. php:method:: getCode()

    .. php:method:: getFile()

    .. php:method:: getLine()

    .. php:method:: getTrace()

    .. php:method:: getPrevious()

    .. php:method:: getTraceAsString()

    .. php:method:: __toString()