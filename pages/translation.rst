===========
Translation
===========

CMDealAggregator comes with English language by default. To translate CMDealAggregator to a different language, please follow the following steps:

**Preparation**:

1. Download and install the full package of your language. `www.joomla.org <http://www.joomla.org>`_ is a right place to search.
2. Go to "Extensions" → "Language Manager", you can see your new language is listed. Take a look at "Language Tag" column, you need to remember the language tag of you new language for next steps.

**Translate for back-end:**

3. Go to administrator/components/com_cmdealaggregator/language folder, create a new folder with the name is the tag of your language that you see in step 2.
4. Copy en-GB.com_cmdealaggregator.ini and en-GB.com_cmdealaggregator.sys.ini files in "en-GB" folder into the new folder you've created in step 3 and change “en-GB” in their names to your language tag. Now you can open these INI files and start translating the string in double quotes to your language.

**Translate for front-end:**

5. Go to components/com_cmdealaggregator/language folder, create a new folder with the name is your language tag.
6. Copy en-GB.com_cmdealaggregator.ini in "en-GB" folder into the new folder, change "en-GB" in its name to your language tag you've created in step 5 and then start translating it.

**Change default language:**

7. Go to Extensions -> Language Manager, in "Installed - Site" submenu you set your new language to your default language for front-end. Switch to "Installed - Administrator" submenu, you choose your default language for back-end.

Now your site and our extensions are switched to your new language.

When you translate the INI files, you need to save them in "UTF-8 without BOM" encoding.