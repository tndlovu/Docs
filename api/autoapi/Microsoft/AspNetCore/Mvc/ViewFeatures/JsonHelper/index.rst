

JsonHelper Class
================






Default implementation of :any:`Microsoft.AspNetCore.Mvc.Rendering.IJsonHelper`\.


Namespace
    :dn:ns:`Microsoft.AspNetCore.Mvc.ViewFeatures`
Assemblies
    * Microsoft.AspNetCore.Mvc.ViewFeatures

----

.. contents::
   :local:



Inheritance Hierarchy
---------------------


* :dn:cls:`System.Object`
* :dn:cls:`Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper`








Syntax
------

.. code-block:: csharp

    public class JsonHelper : IJsonHelper








.. dn:class:: Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper
    :hidden:

.. dn:class:: Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper

Constructors
------------

.. dn:class:: Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper
    :noindex:
    :hidden:

    
    .. dn:constructor:: Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper.JsonHelper(Microsoft.AspNetCore.Mvc.Formatters.JsonOutputFormatter, System.Buffers.ArrayPool<System.Char>)
    
        
    
        
        Initializes a new instance of :any:`Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper` that is backed by <em>jsonOutputFormatter</em>.
    
        
    
        
        :param jsonOutputFormatter: The :any:`Microsoft.AspNetCore.Mvc.Formatters.JsonOutputFormatter` used to serialize JSON.
        
        :type jsonOutputFormatter: Microsoft.AspNetCore.Mvc.Formatters.JsonOutputFormatter
    
        
        :param charPool: 
            The :any:`System.Buffers.ArrayPool\`1` for use with custom :any:`Newtonsoft.Json.JsonSerializerSettings` (see 
            :dn:meth:`Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper.Serialize(System.Object,Newtonsoft.Json.JsonSerializerSettings)`\).
        
        :type charPool: System.Buffers.ArrayPool<System.Buffers.ArrayPool`1>{System.Char<System.Char>}
    
        
        .. code-block:: csharp
    
            public JsonHelper(JsonOutputFormatter jsonOutputFormatter, ArrayPool<char> charPool)
    

Methods
-------

.. dn:class:: Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper.Serialize(System.Object)
    
        
    
        
        :type value: System.Object
        :rtype: Microsoft.AspNetCore.Html.IHtmlContent
    
        
        .. code-block:: csharp
    
            public IHtmlContent Serialize(object value)
    
    .. dn:method:: Microsoft.AspNetCore.Mvc.ViewFeatures.JsonHelper.Serialize(System.Object, Newtonsoft.Json.JsonSerializerSettings)
    
        
    
        
        :type value: System.Object
    
        
        :type serializerSettings: Newtonsoft.Json.JsonSerializerSettings
        :rtype: Microsoft.AspNetCore.Html.IHtmlContent
    
        
        .. code-block:: csharp
    
            public IHtmlContent Serialize(object value, JsonSerializerSettings serializerSettings)
    

