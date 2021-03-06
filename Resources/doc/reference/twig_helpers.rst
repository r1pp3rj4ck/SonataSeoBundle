Twig Helpers
============

Here are the Twig helpers you can use in your layout:

Render the page title
^^^^^^^^^^^^^^^^^^^^^

.. code-block:: jinja

    {{ sonata_seo_title() }}

This will render the page title as follows:

.. code-block:: html

    <title>My custom title</title>

Render page metadatas
^^^^^^^^^^^^^^^^^^^^^

.. code-block:: jinja

    {{ sonata_seo_metadatas() }}

This will render page metadata as follows:

.. code-block:: html

    <meta name="my-meta-name" content="my-value" />

Render HTML attributes
^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: jinja

    {{ sonata_seo_html_attributes() }}

This will render page HTML attributes as follows: ``my-attribute="my-value"``

Render head attributes
^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: jinja

    {{ sonata_seo_head_attributes() }}

This will render page head attributes as follows: ``my-attribute="my-value"``

Render canonical link
^^^^^^^^^^^^^^^^^^^^^

.. code-block:: jinja

    {{ sonata_seo_link_canonical() }}

This will render the page canonical link as follows:

.. code-block:: html

    <link rel="canonical" href="http://www.example.com/"/>

Render alternates languages
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: jinja

    {{ sonata_seo_lang_alternates() }}

This will render page alternate languages as follows:

.. code-block:: html

    <link rel="alternate" href="http://www.example.com/en" hreflang="en"/>
