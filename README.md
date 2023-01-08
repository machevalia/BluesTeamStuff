# BluesTeamStuff
Blue Team Tricks &amp; Tips I have come across and actually find useful.

1. Find potentially malicious PHP webshells starting at /var/www (modify directory as needed)
'''
udo grep -RPn "(passthru|shell_exec|system|phpinfo|base64_decode|chmod|mkdir|fopen|fclose|readfile|php_uname|eval|preg_replace|exif_read_data) *\(" /var/www
'''
