.. include:: /Includes.rst.txt
.. _columns-folder-properties-fieldControl:

============
fieldControl
============

The field of type folder can enable all common
:ref:`field control options <tca_property_fieldControl>`. Furthermore the
following are available:

.. confval:: elementBrowser

   :Path: $GLOBALS['TCA'][$table]['columns'][$field]['config']['fieldControl']
   :type: array
   :Scope: fieldControl

   The element browser field control used in :code:`type='folder'` renders a
   button to open an element browser to choose a folder.

   It is enabled by default if rendering a folder element.
