Model view
==========

This is the guide for the model view in NEST Desktop.

.. image:: /_static/img/thumbnails/model-view.png
   :align: left
   :target: #

Below the icon for the project view, you can see the one of the model view, where you can :ref:`read the model
description <model-view-model-documentation>`, :ref:`explore model activities <model-view-model-explorer>` or :ref:`edit
model configurations <model-view-model-editor>`.

|br|

Models menu
-----------

.. image:: /_static/img/screenshots/model/models-menu.png
   :align: left

By clicking the right mouse button on the model icon, a menu appears where you can select actions for models.

|br|

.. _model-view-model-dialog:

Model dialog
------------

You can import models from various sources, e.g. a file you uploaded from you computer, a file from a GitHub repository
or from a specified URL.

.. image:: /_static/img/screenshots/model/models-import.png
   :target: #models-dialog

.. note::
   Model files should be formatted in JSON.

When you select :bdg:`Import from GitHub`, choose an element type and then a JSON file of your desired model group which
includes all functions of synapse currents.

The table shows a list of models from which you can select which ones you want to import.

|br|

.. _model-view-model-navigation-sidebar:

Model navigation sidebar
------------------------

.. image:: /_static/img/screenshots/model/model-nav.png
   :align: left
   :target: #model-navigation-sidebar

In the navigation sidebar you find a :ref:`model-view-model-toolbar` and then :ref:`model-view-model-list`.

You can select a model to read its documentation, its activity or to edit its configuration.

|br|

.. _model-view-model-toolbar:

Model toolbar
^^^^^^^^^^^^^

.. image:: /_static/img/screenshots/model/model-toolbar.png
   :target: #model-toolbar

At the top of the navigation sidebar, you see a toolbar containing buttons to reload (|reload|), export (|export|),
import (|import|), delete (|delete-models|) or reset (|reset|) multiple models.

|br|

.. _model-view-model-list:

Model List
^^^^^^^^^^

Above the model list you will find a search field and tags which you can use to filter the models in the list. Selected
filter tags appear as chips under the search field. In order to select a tag you need to click on the `filter` icon left
to the search field. Multiple filter tags can be applied. Selected filter tags can be removed (click on |close|).

|br|

.. _model-view-import-models:

Import models
*************

Go to the model view and find your desired synapse model. Next, click on the icon |vertical-dots|, then select a menu
item |import| :bdg:`import` to import it from GitHub.

|br|

.. _model-view-filter-models:

Filter models
*************

.. image:: /_static/img/screenshots/model/models-filter-tag.png
   :align: right
   :target: #filter-models

It is possible to select filter tags to display only models with certain properties. The following filter tags are available:

Installed:
   Show models which are installed in NEST Desktop

GitHub:
   Show models which are provided in `an own GitHub repository <https://github.com/nest-desktop/nest-desktop-models>`_

Neuron/stimulator/recorder/synapse:
   Show models of the selected element type

|br|

.. _model-view-model-subpages:

Model subpages
--------------



|

.. _model-view-model-documentation:

Model documentation
^^^^^^^^^^^^^^^^^^^

.. image:: /_static/img/screenshots/model/model-doc.png
   :target: #model-documentation

It shows the official user documentation of a selected model which also can be found on
http://nest-simulator.readthedocs.io/en/latest/models/.

|

.. _model-view-model-explorer:

Model explorer
^^^^^^^^^^^^^^

.. image:: /_static/img/screenshots/model/model-explorer.png
   :target: #model-explorer

You can explore the activity dynamics of **neuron** models only.

.. image:: /_static/img/screenshots/model/model-explorer-projects.png
   :target: #model-explorer
   :align: left

First, choose a simulation to see the neuronal response to a specific stimulus device.

Then start the simulation by clicking on the :bdg:`SIMULATE` button.

You can use the code editor to see changes in activity.

.. note::
   It is important to disable the Insite pipeline for the simulation (in the settings).


|br|

.. _model-view-model-editor:

Model editor
^^^^^^^^^^^^

The model editor allows you to make changes in parameter specifications, e.g. default value, unit, label or inputs.

.. image:: /_static/img/screenshots/model/model-editor.png
   :target: #model-editor


.. |close| image:: /_static/img/icons/close-circle.svg
   :alt: close
   :height: 17.6px
   :target: #

.. |delete-models| image:: /_static/img/icons/trash-can-outline.svg
   :alt: delete models
   :height: 17.6px
   :target: #

.. |delete| image:: /_static/img/icons/delete.svg
   :alt: delete
   :height: 17.6px
   :target: #

.. |duplicate| image:: /_static/img/icons/content-duplicate.svg
   :alt: duplicate
   :height: 17.6px
   :target: #

.. |export| image:: /_static/img/icons/export.svg
   :alt: export
   :height: 17.6px
   :target: #

.. |import| image:: /_static/img/icons/import.svg
   :alt: import
   :height: 17.6px
   :target: #

.. |new| image:: /_static/img/icons/plus.svg
   :alt: plus
   :height: 17.6px
   :target: #

.. |reload| image:: /_static/img/icons/reload.svg
   :alt: reload
   :height: 17.6px
   :target: #

.. |rename| image:: /_static/img/icons/pencil-outline.svg
   :alt: rename
   :height: 17.6px
   :target: #

.. |reset| image:: /_static/img/icons/database-refresh-outline.svg
   :alt: reset
   :height: 17.6px
   :target: #

.. |save-ok| image:: /_static/img/icons/content-save-check-outline.svg
   :alt: save-ok
   :height: 17.6px
   :target: #

.. |unload| image:: /_static/img/icons/power.svg
   :alt: unload
   :height: 17.6px
   :target: #

.. |vertical-dots| image:: /_static/img/icons/dots-vertical.svg
   :alt: vertical-dots
   :height: 17.6px
   :target: #
