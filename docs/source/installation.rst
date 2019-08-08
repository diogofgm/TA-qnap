============
Installation
============

Install the QNAP Add-on for Splunk
==================================
- Get the QNAP Add-on for Splunk by downloading it from `Splunkbase`_ or browsing to it using the app browser within Splunk Web.
- Determine where and how to install this add-on in your deployment, using the tables on this page.
- Perform any prerequisite steps before installing, if required and specified in the tables below.
- Complete your installation.


Distributed deployments
-----------------------
Reference the tables below to determine where and how to install this add-on in a distributed deployment of Splunk Enterprise or any deployment for which you are using forwarders to get your data in. Depending on your environment, your preferences, and the requirements of the add-on, you may need to install the add-on in multiple places. 

Where to install this add-on
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Unless otherwise noted, all supported add-ons can be safely installed to all tiers of a distributed Splunk platform deployment. See `Where to install Splunk add-ons`_ in Splunk Add-ons for more information.

This table provides a reference for installing this specific add-on to a distributed deployment of Splunk Enterprise. 

.. list-table::
   :header-rows: 1
   
   * - Splunk platform component
     - Supported
     - Required
     - Comments
   * - Search Heads
     - Yes
     - Yes
     - Install this add-on to all search heads.
   * - Indexers
     - Yes
     - Optional
     - Required for the parsing operations (sourcetype renaming) if the data is not coming from a heavy forwarder.
   * - Heavy Forwarders
     - Yes
     - Yes
     - Required for the parsing operations (sourcetype renaming).
   * - Universal Forwarders
     - No
     - No
     - This add-on requires heavy forwarders.


Distributed deployment compatibility
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
This table provides a quick reference for the compatibility of this add-on with Splunk distributed deployment features.

.. list-table::
   :header-rows: 1
   
   * - Distributed deployment feature
     - Supported
     - Comments
   * - Search Head Clusters
     - Yes
     - You can install this add-on on a search head cluster for all search-time functionality.
   * - Indexer Clusters
     - Yes
     - 
   * - Deployment Server
     - Yes
     - Supported for deploying via Deployment server
     

Installation walkthroughs
-------------------------
The Splunk Add-Ons manual includes an `Installing add-ons`_ guide that helps you successfully install any add-on to your Splunk platform.
For a walkthrough of the installation procedure, follow the link that matches your deployment scenario: 

- `Single-instance Splunk Enterprise`_
- `Distributed Splunk Enterprise`_
- `Splunk Cloud`_




.. _Splunkbase: https://splunkbase.splunk.com/app/0000/
.. _Where to install Splunk add-ons: http://docs.splunk.com/Documentation/AddOns/released/Overview/Wheretoinstall
.. _Installing add-ons: http://docs.splunk.com/Documentation/AddOns/released/Overview/Installingadd-ons

.. _Single-instance Splunk Enterprise: http://docs.splunk.com/Documentation/AddOns/released/Overview/Singleserverinstall
.. _Distributed Splunk Enterprise: http://docs.splunk.com/Documentation/AddOns/released/Overview/Distributedinstall
.. _Splunk Cloud: http://docs.splunk.com/Documentation/AddOns/released/Overview/SplunkCloudinstall