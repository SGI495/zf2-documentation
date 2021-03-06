.. EN-Revision: none
.. _zend.server.introduction:

Введение
========

Семейство классов *Zend_Server* предоставляет набор функциональных
возможностей для различных серверных классов, в которые
входят *Zend\XmlRpc\Server*, *Zend\Rest\Server*, *Zend\Json\Server* и *Zend\Soap\Wsdl*.
*Zend\Server\Interface* предоставляет интерфейс, который имитирует класс
*SoapServer* из PHP 5; все серверные классы должны реализовывать этот
интерфейс для того, чтобы предоставлять стандартный серверный
API.

*Zend\Server\Reflection* предоставляет стандарный механизм для
выполнения интроспекции функций и классов, используемых как
обратные вызовы (callbacks) с серверными классами, и предоставляет
данные, пригодные для использования с методами *getFunctions()* и
*loadFunctions()* интерфейса *Zend\Server\Interface*.


