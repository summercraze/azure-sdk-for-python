Microsoft Azure SDK for Python
==============================

.. image:: https://img.shields.io/pypi/v/azure.svg?maxAge=2592000
    :target: https://pypi.python.org/pypi/azure/

.. image:: https://img.shields.io/pypi/pyversions/azure.svg?maxAge=2592000
    :target: https://pypi.python.org/pypi/azure/

.. image:: http://www.quantifiedcode.com/api/v1/project/7e8a70bc3a1d445b95561f55712fee5a/badge.svg
    :target: http://www.quantifiedcode.com/app/project/7e8a70bc3a1d445b95561f55712fee5a

.. image:: https://travis-ci.org/Azure/azure-sdk-for-python.svg?branch=master
    :target: https://travis-ci.org/Azure/azure-sdk-for-python

.. image:: https://ci.appveyor.com/api/projects/status/m51hrgewcxknxhsd/branch/master?svg=true
    :target: https://ci.appveyor.com/project/lmazuel/azure-sdk-for-python/branch/master

This project provides a set of Python packages that make it easy to
access the Microsoft Azure components such as ServiceManagement, Storage\*, and ServiceBus.

The SDK supports Python 2.7, 3.3, 3.4 and 3.5.

\*Looking for the Azure Storage client library?  It moved to a `new GitHub repository <https://github.com/Azure/azure-storage-python>`__.

See important information if you're currently using this SDK < 1.0 in `this issue <https://github.com/Azure/azure-sdk-for-python/issues/440>`__.


INSTALLATION
============

**The latest recommended release is currently a release candidate, tell this to pip to install it!**

The `azure` bundle meta-package will install all Azure SDKs at once:

- Use the ``--pre`` flag: ``pip install --pre azure``

- Specify the version:  ``pip install azure==2.0.0rc5``

You can also install only what you exactly need:

- Use the ``--pre`` flag: ``pip install --pre azure-mgmt-compute``

- Specify the version:  ``pip install azure-mgmt-compute==0.30.0rc5``

If you want to install ``azure`` from source::

    git clone git://github.com/Azure/azure-sdk-for-python.git
    cd azure-sdk-for-python
    python setup.py install

DISCLAIMER
==========

This is a release candidate. However, the core packages, from code quality/completeness perspectives can at this time be considered "stable" - 
it will be officially labeled as such in September (in sync with other languages).

We are not planning on any further major changes until then.

The following packages are still labeled "preview" but can be considered "stable":

- azure-mgmt-resource 0.30.0rc5
- azure-mgmt-compute 0.30.0rc5
- azure-mgmt-network 0.30.0rc5
- azure-mgmt-storage 0.30.0rc5

The following packages are already released as "stable" and are officially production ready:

- azure-batch 1.0.0
- azure-mgmt-batch 1.0.0
- azure-servicebus 0.20.3
- azure-servicemanagement-legacy 0.20.4

All other packages are real "preview" packages. Please send us your feedback!

Features
========

-  `Service Bus Runtime </azure-servicebus>`__

-  `Service Management </azure-servicemanagement-legacy>`__

-  `Azure Active Directory Graph RBAC </azure-graphrbac>`__

-  `Batch </azure-batch>`__

-  `Resource Management </azure-mgmt>`__

   -  `Authorization </azure-mgmt-authorization>`__
   -  `Batch </azure-mgmt-batch>`__
   -  `CDN </azure-mgmt-cdn>`__
   -  `Compute </azure-mgmt-compute>`__
   -  Apps
   
       -  `Logic Apps </azure-mgmt-logic>`__
       -  `Web Apps </azure-mgmt-web>`__

   -  `Network </azure-mgmt-network>`__
   -  `Notification Hubs </azure-mgmt-notificationhubs>`__
   -  `Redis Cache </azure-mgmt-redis>`__
   -  `Resource </azure-mgmt-resource>`__
   -  `Scheduler </azure-mgmt-scheduler>`__
   -  `Storage </azure-mgmt-storage>`__


Usage
=====

For detailed documentation, please view our `documentation on ReadTheDocs <http://azure-sdk-for-python.readthedocs.org>`__.

For further examples please visit the `Microsoft Azure Python Developer Center <http://azure.microsoft.com/en-us/develop/python/>`__.


Need Help?
==========

Be sure to check out the Microsoft Azure `Developer Forums on Stack Overflow <http://go.microsoft.com/fwlink/?LinkId=234489>`__
if you have trouble with the provided code.


Contribute Code or Provide Feedback
===================================

If you would like to become an active contributor to this project please
follow the instructions provided in `Microsoft Azure Projects Contribution Guidelines <http://azure.github.io/guidelines/>`__.

If you encounter any bugs with the library please file an issue in the
`Issues <https://github.com/Azure/azure-sdk-for-python/issues>`__
section of the project.


Learn More
==========

`Microsoft Azure Python Developer Center <http://azure.microsoft.com/en-us/develop/python/>`__
