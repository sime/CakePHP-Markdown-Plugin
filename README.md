Markdown CakePHP Plugin
=======================

A CakePHP Plugin for rendering Markdowns views as HTML

INSTALLATION
------------

Install the plugin in the app/Plugin/Markdown directory and insert the
following line into bootstrap.php

    CakePlugin::load('Markdown');

USAGE
-----

Set <code>Markdown.Markdown</code> as the <code>$this->viewClass</code> in
the action which view is marked up in Markdown syntax.

    public function api()
    {
        $this->viewClass = 'Markdown.Markdown';
    }

BACKSTORY
---------

The current CakePHP Markdown Plugins/Helpers seem like a lot of fiddling
to support Markdown. In my mind, quickly changing the viewClass is the
simplest and cleanest way of support Markdown.

Happy to discuss if you have any other ideas.
