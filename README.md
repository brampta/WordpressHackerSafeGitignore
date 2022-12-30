This .gitignore will:
- ignore any file or folder created under wp-content/
- except for /wp-content/plugins/, wp-content/mu-plugins/, wp-content/themes/, wp-content/languages/ and wp-content/maintenance/ which will NOT be ignored
- any .php or .phtml file will not be ignored either even if its in an ignored folder (so hackers cannot just hide a php file in an ignored folder)

also note that with this .gitignore:
- your WP core is NOT ignored by git, or anything outside of the wp-content folder
- of course config files, log files, etc are ignored
