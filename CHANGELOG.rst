Changelog
=========

Version 1.4.0
-------------

- Updated `ChangedLogEntryManager` and `NoLogEntryManager` to handle the removal of the `single_object` argument in Django 5.1.7.
- Ensured compatibility with Django versions both before and after 5.1.7.

1.3.0 (2024-08-10)
------------------
* Added support for Django 5.1
* Dropped support for Django 3.2

1.2.0 (2024-03-03)
------------------
* Added option to ignore logs where no changes were made.
* Added link to log entry user in admin list of log entries.

1.1.0 (2023-12-18)
------------------
* Only display content types to filter that actually have a related log entry.
* Added support for Django 4.2 and 5.0
* Dropped support for Django 2.2, 3.0 and 3.1

1.0.2 (2021-04-24)
------------------
* Added support for Django 3.2 and Python 3.9
* Dropped support for Django 2.1 and Python 3.5

1.0.1 (2020-08-16)
------------------
* Added support for Django 3.1

1.0.0 (2020-03-03)
------------------
* Initial release
