---
title: Installing Zotero
layout: default
---

Chapter Contents
----------------
* This will become a table of contents (this text will be scraped).
{:toc}

#Installing Zotero

Zotero is available in several flavors. There are two versions of the desktop client: **Zotero for Firefox**, an add-on for the Firefox browser, and **Zotero Standalone**, a regular application that doesn't require Firefox to run. You can also access and edit your Zotero libraries on the [zotero.org](http://zotero.org) website. There are currently no official mobile Zotero apps, although there are several third-party apps.

The desktop clients and the website have somewhat different roles. The clients have by far the most features, but require installation on a Mac, Windows, or Linux computer. The website has a more limited feature set, but allows you to access your Zotero library from any modern browser. With Zotero syncing, your local client and online libraries can be kept in sync, allowing you to use both.

You might be wondering which desktop client to use. Zotero was originally developed as a Firefox add-on. Because of this pedigree, and because Firefox is still the most extensible browser on the market, **Zotero for Firefox** has several features that are absent from **Zotero Standalone**. On the other hand, **Zotero Standalone** is typically somewhat faster, and connects easily to Firefox, Google Chrome, and Safari. For a full comparison, see the table below:

<table>
<tr>
<th>Zotero for Firefox</th>
<th>Zotero Standalone</th>
</tr>
<tr>
<td>Integrates into Firefox, with the Zotero pane appearing minimized, in split-view, or in a dedicated tab</td>
<td>Runs as a dedicated program, and doesn't require Firefox to be installed</td>
</tr>
<tr>
<td>Doesn't connect to other browsers</td>
<td>Can connect to Firefox, Google Chrome, and Safari</td>
</tr>
<tr>
<td>Has better proxy support for gated resources</td>
<td>Starts up faster</td>
</tr>
<tr>
<td>Has better web translators</td>
<td>Runs faster</td>
</tr>
<tr>
<td>Can automatically import online RIS/Refer files (so you don't have to download these to the desktop first)</td>
<td>Doesn't slow down the browser</td>
</tr>
<tr>
<td>Allows you to print and customize Zotero reports</td>
<td></td>
</tr>
</table>

If you have a hard time choosing between the two clients, or simply want to have the best of both worlds, you can install **Zotero for Firefox** and **Zotero Standalone** side-by-side. Upon installation of the second client, you will be asked whether you wish to share a single Zotero database between the two clients, or have each client have its own.

##Installing Zotero for Firefox

The first step in installing **Zotero for Firefox** is installing Firefox, available at [mozilla.org/firefox](http://www.mozilla.org/firefox/).

Then, visit [zotero.org/download](http://zotero.org/download/) with Firefox and click the download button for **Zotero for Firefox**. If you see a pop-up saying “Firefox prevented this site (www.zotero.org) from asking you to install software on your computer.”, click the “Allow” button. Wait for the add-on to download, and click the “Install Now” button in the installation pop-up window. Complete the installation by restarting Firefox.

###Firefox version compatibility

Firefox is frequently updated to add new features, squash bugs, and implement security fixes. Browsing the internet with an outdated browser is a safety risk, and we strongly recommend that you keep your browser up-to-date. The latest version of Zotero is always compatible with the latest version of Firefox.

You may encounter compatibility problems if you try to use Zotero with the development releases of Firefox (the Aurora and Beta channels). The Firefox Extended Support Release is typically supported by the latest Zotero release.

###Word processor plugins

Zotero's word processor plugins make it easy to cite Zotero items in Microsoft Word and LibreOffice. To install one of these plugins for **Zotero for Firefox**, visit [zotero.org/download](http://zotero.org/download/) with Firefox after **Zotero for Firefox** is installed, and click the link to the plugins webpage. Look for the right version for your word processor and operating system, and click that version's installation link.

##Installing Zotero Standalone

To install **Zotero Standalone**, visit [zotero.org/download](http://zotero.org/download/) and click the download link for **Zotero Standalone**. The webpage automatically preselects the version suited for your operating system. Then:

* *Windows* - open the downloaded .exe installer and follow the instructions
* *Mac* - drag the downloaded .dmg file into your Applications folder
* *Linux* - uncompress the downloaded .tar.bz2 tarball file and run "zotero"

###Connectors

After installing Zotero Standalone, you can install one or more Zotero connectors. Connectors are browser add-ons that allow you to save items directly from your web browser to Zotero Standalone. There are connectors for Google Chrome, Safari, and Firefox. The Firefox connector is special: it is actually a full version of **Zotero for Firefox** (see *Installing Both Clients* below).

To install a connector, visit [zotero.org/download](http://zotero.org/download/) and click the installation link for your browser(s) of choice.

When **Zotero Standalone** is closed (or not installed), the Google Chrome and Safari connectors will save items directly to your online Zotero library.

###Bookmarklet

The Zotero bookmarklet allows you to save items from any browser directly to your online Zotero library. The features of the bookmarklet are more limited than those of the clients and connectors, but don't require any installation of software.

To set up the bookmarklet, follow the official [bookmarklet instructions](http://www.zotero.org/downloadbookmarklet).

###Word processor plugins

Word processor plugins for Microsoft Word and LibreOffice are included with **Zotero Standalone**.

##Installing Both Clients

The first time you install a Zotero client a new data directory will be created on your computer, in which the client stores its data. When you install a second client (**Zotero for Firefox** if **Zotero Standalone** is already installed, or **Zotero Standalone** if **Zotero for Firefox** is already installed), the second client will ask you whether you want it to share the data directory of the first client.

If the clients don't share the same data directory, they will have separate libraries, although you can still keep the two clients synchronized via the internet using Zotero Sync.

If the clients do share the same data directory, **Zotero for Firefox** will behave as a connector whenever **Zotero Standalone** is open. You won't be able to open the Zotero pane in Firefox, and clicking the Zotero logo in the Firefox Add-on Bar will open **Zotero Standalone**. Features specific to **Zotero for Firefox** are disabled. When you save items in Firefox, they end up directly in **Zotero Standalone**. In contrast, when **Zotero Standalone** is closed, **Zotero for Firefox** behaves as a regular full-featured client.

##Updating Clients

By default, **Zotero for Firefox** and **Zotero Standalone** update automatically. To manually check for updates for **Zotero for Firefox**, open the Add-ons Manager of Firefox (**Tools** menu > "Add-ons") and select "Check for Updates" in the gear menu. In **Zotero Standalone**, select "Check for Updates…" in the **Zotero** menu.

Also by default, the data directories of **Zotero for Firefox** and **Zotero Standalone** are stored in different locations than the clients themselves. It is therefore generally safe to uninstall and reinstall the Zotero clients (when uninstalling a client, you may be asked if your Zotero data should be deleted as well; don't agree to this if you wish to keep your data). While relatively low-risk, we still strongly recommend that you make a backup before reinstalling clients.

##Troubleshooting

If you experience problems installing the Zotero clients, see the official Zotero instructions on [troubleshooting installation issues](http://www.zotero.org/support/installation#troubleshooting_installation_issues).
