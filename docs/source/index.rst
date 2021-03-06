.. Blacksmith documentation master file, created by
   sphinx-quickstart on Sat Sep 14 23:37:29 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

The Blacksmith Project
======================

The Blacksmit project focuses on providing dynamic easy-to-use templates for security researches to model and provision resources needed to automatically deploy applications in the cloud.
It currently leverages "`AWS CloudFormation <https://aws.amazon.com/cloudformation/>`_" to model infrastructure and architecture of applications in AWS.
Even though the goal is to deploy resources in the cloud, the project also hosts Docker files to deploy container-based applications.
Those docker containers can then be also used with resources in the cloud to expedite deployment.

Goals
*****

* Expedite research by providing dynamic templates to deploy applications in the cloud.
* Translate favorite applications or tools into cloud templates for developing and testing.
* Replicate research environments for training purposes
* Learn more about AWS CloudFormation

.. toctree::
   :maxdepth: 2
   :caption: Getting Started:

   AWS Setup <aws_setup>
   Azure Setup <azure_cli_setup>

.. toctree::
   :maxdepth: 2
   :caption: Available Templates:

   Mordor Environments <mordor>
   SilkETW <silketw>
   ATT&CK Website <attack_website>

.. toctree::
   :maxdepth: 2
   :caption: Licenses:

   GNU General Public License V3 <license>
