===========================
OpenStack API Documentation
===========================

Use the OpenStack APIs to launch server instances, create images, assign
metadata to instances and images, create storage containers and objects, and
complete other actions in your OpenStack cloud.

Current API versions
--------------------

`Bare Metal API v1 <http://developer.openstack.org/api-ref/baremetal/>`__ (microversions)

`Block Storage API v2 <http://developer.openstack.org/api-ref/block-storage/v2/>`__

`Clustering API v1 <http://developer.openstack.org/api-ref/clustering/>`__

`Compute API <http://developer.openstack.org/api-ref/compute/>`__ (microversions)

`Data Processing v1.1 <http://developer.openstack.org/api-ref/data-processing/>`__

`Database Service API v1.0 <http://developer.openstack.org/api-ref/database/>`__

`Domain Name Server (DNS) API v2 <http://developer.openstack.org/api-ref/dns/>`__

`Identity API v3 <http://developer.openstack.org/api-ref/identity/v3>`__

`Identity API v3 extensions <http://developer.openstack.org/api-ref/identity/v3-ext>`__

`Image service API v2 <http://developer.openstack.org/api-ref/image/v2>`__

`Networking API v2.0 <http://developer.openstack.org/api-ref/networking/v2>`__

`Object Storage API v1 <http://developer.openstack.org/api-ref/object-storage>`__

`Orchestration API v1 <http://developer.openstack.org/api-ref/orchestration/v1/>`__

`Shared File Systems API v2 <http://developer.openstack.org/api-ref/shared-file-systems>`__ (microversions)

.. note:: The Shared File Systems API v1 is functionally identical to the
   Shared File Systems API v2. Subsequent API v2 microversions, such as v2.1,
   differ from API v1.

Supported API versions
----------------------

`Image service API v1 <http://developer.openstack.org/api-ref/image/v1>`__

Deprecated API versions
-----------------------

`Block Storage API v1 <http://developer.openstack.org/api-ref/block-storage/v1/>`__

`Identity API v2.0 <http://developer.openstack.org/api-ref/identity/v2>`__

`Identity admin API v2.0 <http://developer.openstack.org/api-ref/identity/v2-admin>`__

`Identity API v2.0 extensions <http://developer.openstack.org/api-ref/identity/v2-ext>`__

.. todo: telemetry link

The API status reflects the state of the endpoint on the service.

* Current indicates a stable version that is up-to-date, recent, and might
  receive future versions. This endpoint should be prioritized over all
  others.
* Supported is a stable version that is available on the server. However, it
  is not likely the most recent available and might not be updated or might
  be deprecated at some time in the future.
* Deprecated is a stable version that is still available but is being
  deprecated and might be removed in the future.
* Experimental is not a stable version. This version is under development or
  contains features that are otherwise subject to change. For more
  information about API status values and version information, see
  `Version Discovery <https://wiki.openstack.org/wiki/VersionDiscovery>`__.
* Microversions indicates that the API follows a `pattern established by
  the Compute service <http://developer.openstack.org/api-guide/compute/microversions.html>`__ to
  enable small, documented changes to the API on a resource-by-resource
  basis.

API quick-start examples
------------------------

With the `TryStack <http://www.trystack.org/>`__ OpenStack
installation, these services work together in the background of the
installation, and many of these examples work on TryStack.

After you authenticate through Identity, you can use the other OpenStack
APIs to create and manage resources in your OpenStack cloud. You can
launch instances from images and assign metadata to instances through
the Compute API or the **openstack** command-line client.

To begin sending API requests, use one of the following methods:

-  **cURL**

   A command-line tool that lets you send HTTP requests and receive
   responses. See the section called :ref:`openstack_API_quick_guide`.

-  **OpenStack command-line client**

   The OpenStack project provides a command-line client that enables
   you to access APIs through easy-to-use commands. See the section
   called :ref:`client-intro`.

-  **REST clients**

   Both Mozilla and Google provide browser-based graphical interfaces
   for REST. For Firefox, see
   `RESTClient <https://addons.mozilla.org/en-US/firefox/addon/restclient/>`__.
   For Chrome, see
   `rest-client <http://code.google.com/p/rest-client/>`__.

-  **OpenStack Python Software Development Kit (SDK)**

   Use this SDK to write Python automation scripts that create and
   manage resources in your OpenStack cloud. The SDK implements Python
   bindings to the OpenStack API, which enables you to perform
   automation tasks in Python by making calls on Python objects rather
   than making REST calls directly. All OpenStack command-line tools are
   implemented by using the Python SDK. See `OpenStack Python
   SDK <http://docs.openstack.org/user-guide/sdk.html>`__ in the
   *OpenStack End User Guide*.

.. toctree::
   :maxdepth: 2

   api-quick-start




