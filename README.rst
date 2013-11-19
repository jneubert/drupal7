Drupal 7 - Content Management Framework
=======================================

*TurnKey Linux applicance, adapted for the SWIB13* `Linked Data Publication with Drupal`_ *workshop.*

*For the workshop participants: Please follow the instructions on the* Installation_ *page.*

`Drupal`_ is an open source content management platform licensed under
the GPL. Equipped with a powerful blend of features, Drupal can support
a variety of websites ranging from personal blogs, corporate brochures
and large community-driven websites.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Drupal 7 configurations:
   
   - Installed from upstream source code to /var/www/drupal7
   - Includes drush for command line administration and configuration.

- Bundled popular Drupal 7 modules and dependencies (installed to
  /var/www/drupal7/sites/all/modules):
   
   - `Panels`_: Drag and drop customized layouts for pages, nodes and
     blocks.
   - `Backup and migrate`_: Backup and restore your Drupal site
     on-demand or on a schedule.
   - `Devel`_: A suite of helper modules for Drupal module and theme
     developers.
   - `Drush`_: a command line shell and Unix scripting interface for
     Drupal.
   - `Ckeditor`_: Enables CKeditor (a WYSIWYG editor) instead of plain
     text fields.
   - `Imce`_: Powerful image file uploader and browser, with support for
     on the fly resizing.
   - `Recaptcha`_: Thwart spammers by adding image or text based
     CAPTCHAs to your site.
   - `PathAuto`_: Auto-generate search engine friendly URLs (SEO).
   - `GlobalRedirect`_: Alias 301 redirects, prevents duplicate content.
     (SEO)
   - `FiveStar`_: Simple five-star voting widget for nodes.
   - `Webform`_: Create forms and questionnaires.
   - `Logintoboggan`_: Improves Drupal's login system.
   - `Admin menu`_: Adds dropdown administration menu to the top of the
     screen.
   - `Tagadelic`_: Makes weighted tag clouds from your taxonomy terms.
   - `Lightbox2`_: Places images above your current page, not within.
   - `Google analytics`_: Adds Google Analytics js tracking code to all
     your site's pages.
   - `Advanced\_help`_: Improves the Drupal help system.
   - `Rules`_: Lets you define conditionally executed actions based on
     occurring events.
   - `Jquery\_ui`_: provides jQuery UI plugin to other Drupal modules.
   - `Token`_: Provides a shared API for replacement of textual
     placeholders with actual data.
   - `Email`_: Support email field in custom content types.
   - `Link`_: Support URL link field in custom content types.
   - `Date`_: Support Date field in custom content types.

- Additional Drupal modules for the workshop:

   - `RDF Extensions`_: User Interface for creating RDF mappings and 
     additional serialization formats (Turtle, RDF/XML, Ntriples)
   - `SPARQL`_: Publish data via a SPARQL endpoint
   - `Web Taxonomy`_: Reference external authority data as taxonomy
   - `Economics Taxonomies`_: Example Taxonomies (STW, GND persons) (experimental)
   - `SPARQL Views`_: Access remote SPARQL endpoints via Views
   - `Schema.org`_: Dedicated schema.org markup
   - `RESTful Web Services`_: Dependency for RDF serializations
   - `HTTP Client`_: Dependency for Econonmics Taxonomies
   - `Strongarm`_, `Recipe`_: Dependencies for Schema.org
   - ...

- SSL support out of the box.
- `PHPMyAdmin`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, phpMyAdmin: username **root**
-  Drupal 7: username **admin**

.. _Installation: https://github.com/jneubert/tkldev-drupal7-lod-swib13/wiki/Installation 
.. _Drupal: http://drupal.org
.. _TurnKey Core: http://www.turnkeylinux.org/core
.. _Panels: http://drupal.org/project/panels
.. _Backup and migrate: http://drupal.org/project/backup_migrate
.. _Devel: http://drupal.org/project/devel
.. _Drush: http://drupal.org/project/drush
.. _Ckeditor: http://drupal.org/project/ckeditor
.. _Imce: http://drupal.org/project/imce
.. _Recaptcha: http://drupal.org/project/recaptcha
.. _PathAuto: http://drupal.org/project/pathauto
.. _GlobalRedirect: http://drupal.org/project/globalredirect
.. _FiveStar: http://drupal.org/project/fivestar
.. _Webform: http://drupal.org/project/webform
.. _Logintoboggan: http://drupal.org/project/logintoboggan
.. _Admin menu: http://drupal.org/project/admin_menu
.. _Tagadelic: http://drupal.org/project/tagadelic
.. _Lightbox2: http://drupal.org/project/lightbox2
.. _Google analytics: http://drupal.org/project/google_analytics
.. _Advanced\_help: http://drupal.org/project/advanced_help
.. _Rules: http://drupal.org/project/rules
.. _Jquery\_ui: http://drupal.org/project/jquery_ui
.. _Token: http://drupal.org/project/token
.. _Email: http://drupal.org/project/email
.. _Link: http://drupal.org/project/link
.. _Date: http://drupal.org/project/date
.. _PHPMyAdmin: http://www.phpmyadmin.net
.. _Linked Data Publication with Drupal: http://swib.org/swib13/programme.php#abs112
.. _RDF Extensions: https://drupal.org/project/rdfx
.. _RESTful Web Services: https://drupal.org/project/restws
.. _SPARQL: https://drupal.org/project/sparql
.. _SPARQL Views: https://drupal.org/project/sparql_views
.. _Web Taxonomy: https://drupal.org/project/web_taxonomy
.. _Economics Taxonomies: https://drupal.org/sandbox/jneubert/1447918
.. _Schema.org: https://drupal.org/project/schemaorg
.. _HTTP Client: https://drupal.org/project/http_client
.. _Strongarm: https://drupal.org/project/strongarm
.. _Recipe: https://drupal.org/project/recipe


