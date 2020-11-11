

********************************************************************************
cli-journal
********************************************************************************

**cli-journal** is a script to make keeping a journal easier on the command
line.

How to use:

- Clone git repo

- Create a soft link to the ``journal`` script to your home directory (``ln -s
  cli-journal/journal ~/journal``).

- Optionally, create a template file for your journal entries
  (``journal/_template.rst``). All new entries will start with this base
  template.

- Execute the script to open the day's journal entry.

Entry file names are simply the ISO date. For example, ``2020-01-01.rst``. This
format makes it easier to write scripts to search or analyze your journal in
the future.
