=======================================
Service tracking: Copy tasks in project
=======================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:e6cf6bd73a6e6db1fa68c76c022901b008ad41f6270d5b5e24e7648523100d6e
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fproject-lightgray.png?logo=github
    :target: https://github.com/OCA/project/tree/14.0/sale_project_service_tracking_copy_tasks
    :alt: OCA/project
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/project-14-0/project-14-0-sale_project_service_tracking_copy_tasks
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/project&target_branch=14.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module add the possibility to create task in an existing project from the sales order through setting the product with a project template with the desired task.

The use case is when a Odoo customer sell the same services with the same task constantly and the task should be linked with existing project. Odoo don't cover this use case as Odoo always create a new project.

**Table of contents**

.. contents::
   :local:

Usage
=====

1. Go to Project > Projects.
2. Create project.
3. Go to Project > Tasks.
4. Create tasks for the project created in step 2.
5. Go to Sales > Products > Products.
6. Create product whose type is service, the service tracking is to copy the task into the sales order project and project template select project created in step 2.
7. Go to Sales > Quotation > Quotation.
8. Create quotation with products created in step 6.
9. Confirm the quotation. The tasks from project templates in products will be created in same project.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/project/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/project/issues/new?body=module:%20sale_project_service_tracking_copy_tasks%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Moduon

Contributors
~~~~~~~~~~~~

* Eduardo de Miguel (`Moduon <https://www.moduon.team/>`__)
* Emilio Pascual (`Moduon <https://www.moduon.team/>`__)

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-shide| image:: https://github.com/shide.png?size=40px
    :target: https://github.com/shide
    :alt: shide
.. |maintainer-EmilioPascual| image:: https://github.com/EmilioPascual.png?size=40px
    :target: https://github.com/EmilioPascual
    :alt: EmilioPascual

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-shide| |maintainer-EmilioPascual| 

This module is part of the `OCA/project <https://github.com/OCA/project/tree/14.0/sale_project_service_tracking_copy_tasks>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
