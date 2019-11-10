---
title: Autosave
helpCategories:
  - General
since: 3.7
---

# Autosave

## Purpose

The autosave feature helps to save an opened database without manual intervention. Furthermore, it synchronizes your local files which are associated with appropriate [shared SQL databases](https://github.com/JabRef/help.jabref.org/tree/1f58696d9081b60bf60823090c7594d67d7f5295/en/SQLDatabase/README.md).

## Activation

![Screenshot of the autosave preferences](../../.gitbook/assets/autosave.png)

You can activate the autosave feature through **Options → Preferences**, and then by choosing **File** on the left panel. At the lower part of the window, a section is dedicated to **AutoSave**.

## Autosave for local databases

If you are working on `.bib` files which are located on your file system, this feature will detect your changes automatically and save them without further intervention.

## Autosave for shared databases

Generally, you are able to save a shared database after connecting to it. This feature enables a full synchronization of your local bib file with the [shared SQL database](https://github.com/JabRef/help.jabref.org/tree/1f58696d9081b60bf60823090c7594d67d7f5295/en/SQLDatabase/README.md) which could simultaneously be used by other collaborators.

## Remarks

By default this feature is disabled for local databases. It has to be kept apart from the [main backup functionality](https://github.com/JabRef/help.jabref.org/tree/1f58696d9081b60bf60823090c7594d67d7f5295/en/Backup/README.md) as the backup is running continuously without users influence.

By using the [gitignore.io](https://www.gitignore.io/) service, you can generate an appropriate `.gitignore` file by opening [https://www.gitignore.io/api/jabref](https://www.gitignore.io/api/jabref).
