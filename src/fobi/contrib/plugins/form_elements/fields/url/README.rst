fobi.contrib.plugins.form_elements.fields.url
---------------------------------------------
A ``Fobi`` URL form field plugin. Makes use of the
``django.forms.fields.URLField`` and ``django.forms.widgets.URLInput`` falling
back to ``django.forms.widgets.TextInput`` for older Django versions.

Installation
~~~~~~~~~~~~
(1) Add ``fobi.contrib.plugins.form_elements.fields.url`` to the
    ``INSTALLED_APPS`` in your ``settings.py``.

    .. code-block:: python

        INSTALLED_APPS = (
            # ...
            'fobi.contrib.plugins.form_elements.fields.url',
            # ...
        )

(2) In the terminal type:

    .. code-block:: sh

        ./manage.py fobi_sync_plugins

(3) Assign appropriate permissions to the target users/groups to be using
    the plugin if ``FOBI_RESTRICT_PLUGIN_ACCESS`` is set to True.
