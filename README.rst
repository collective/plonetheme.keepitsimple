=======================
plonetheme.keepitsimple
=======================


Introduction
============

*plonetheme.keepitsimple* package is an installable Plone_ Theme using the **theming** and **packaging** 
features available in `plone.app.theming`_ to make this theme easily available in `Plone`.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Features
========
- It's a simple Diazo_ package (Zip file).


Installation
============


Add Plone site
--------------

Install Plone 4.x with `plone.app.theming`_ and create a Plone site (if you have not already)
with Diazo theming configured.

.. image:: https://github.com/collective/plonetheme.keepitsimple/raw/master/screenshot0.png
  :width: 1024px
  :alt: Create a Plone site from ZMI
  :align: center


Zip file
--------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download a `zip file <https://raw.github.com/collective/plonetheme.keepitsimple/master/keepitsimple.zip>`_.
2. Import the theme from the Diazo theme control panel.

.. image:: https://github.com/collective/plonetheme.keepitsimple/raw/master/screenshot1.png
  :width: 1024px
  :alt: Import the Diazo theme zip file
  :align: center


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.keepitsimple`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.keepitsimple


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.keepitsimple',
    ],


Enabling the theme
^^^^^^^^^^^^^^^^^^

Browse to ``http://yoursite/Plone/@@theming-controlpanel`` click on ``Enable`` 
on ``Keep It Simple`` theme from the Diazo control panel.

.. image:: https://github.com/collective/plonetheme.keepitsimple/raw/master/screenshot2.png
  :width: 1024px
  :alt: For select the Diazo theme just click on Activate button
  :align: center

That's it!

You should see the layout of the site when viewed in a computer resolution:

.. image:: https://raw.githubusercontent.com/collective/plonetheme.keepitsimple/master/plonetheme/keepitsimple/theme/keepitsimple/preview.png
  :width: 1024px
  :alt: plonetheme.keepitsimple preview
  :align: center


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.keepitsimple/issues
- Source Code: https://github.com/collective/plonetheme.keepitsimple


Collaborations
--------------

- Alex Clark (aclark at aclark dot net).

- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).

- Full Name aka nickname

For an updated list of all the contributors visit: https://github.com/collective/plonetheme.keepitsimple/graphs/contributors


License
=======

This package is licensed under the GPL Version 2.

.. _`Plone`: http://plone.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`Diazo`: http://diazo.org
