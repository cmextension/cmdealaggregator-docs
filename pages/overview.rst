========
Overview
========

CMDealAggregator is a deal aggregator component for Joomla! developed by CMExtension Team.

With CMDealAggregator, your Joomla! website can have a function of a deal feeder – getting deals from social buying websites like `Groupon.com <http://www.groupon.com/>`_ or `LivingSocial.com <http://www.livingsocial.com/>`_, and earn referral credits.

You should have all the following files in the package you downloaded from our website or received
from us:

* **com_cmdealaggregator.zip**: The main component.
* **mod_cmdealaggregator_search.zip**: The module for searching deals.
* **mod_cmdealaggregator_category_list.zip**: The module for listing all categories as a menu module.
* **mod_cmdealaggregator_more_deas.zip**: The module for displaying deals.
* **tagcmdealaggregator2**: The plugin for daily deal tags for ACYMailing's tag system.

This documentation only gives you instructions how to use our extensions. This documentation doesn't mention about basic usages of Joomla!, we consider you've already known how to use Joomla!. You can view
Joomla! Help (menu "Help" -> "Joomla! Help" in Joomla! Administrator section) or visit `Joomla! home
page <http://www.joomla.org/>`_ for documentations about Joomla!.

Technical Requirements
----------------------

* **Joomla! 2.5.x** or **Joomla! 3.x.x**: CM Deal Aggregator is **NOT** compatible with Joomla! 1.x.x. Please check `Joomla!'s Technical Requirements <http://www.joomla.org/technical-requirements.html>`_ for more information. We recommend to latest release of Joomla! for stability and security.
* **Bootstrap 2**: CM Deal Aggregator is **NOT** compatible with Bootstrap 3. Bootstrap 2 is available by default in Joomla! 3.x.x. Bootstrap 2 must be loaded on your site by Joomla! or by your template. You can also load Bootstrap from CM Deal Aggregator itself.
* **XML feed**: CM Deal Aggregator supports plain XML feeds (.xml) or XML feeds which are compressed into GZ files (.gz).

Features
--------

Front-end:

* Deal list page: List all deals on the site, can be filtered by category, location and website.
* Deal detail page: Display information about a specific deal and navigate to the deal's website.
* Deal map page: Browse deal via Google Maps.
* Search for deal by keyword, location, category and website with Search module.
* Share deals via Facebook, Twitter,Google+ and email. Can be disabled in back-end.
* Display deals on any page with More Deals module. Deals can be selected in different ways:

  * Featured deals: Only specified deals are displayed.
  * Random deals: Deals are selected randomly.
  * Popular deals: List the deals which are clicked the most.
  * Ending soon deals: List the deals which will be expired soon.

* Import deals with web based cron job.

Back-end:

* Manage categories, locations, websites, XML feeds and deals.
* Import deals from XML feeds with ease right in Joomla! back-end.
* Import deals with server's cron job.
* Ability to edit deal information after deal is imported.
* Ability to create deal manually.
* Count how many people have clicked to view deals.
* Tools for truncating the tables, deleting the downloaded XML feed files.
