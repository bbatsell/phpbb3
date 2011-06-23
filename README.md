[![phpBB](http://www.phpbb.com/theme/images/logos/blue/160x52.png)](http://www.phpbb.com)

## ABOUT

phpBB is a free bulletin board written in PHP.

## THIS FORK
This fork will be focused on small changes to make phpBB more scalable and highly available.  Planned features include:

- CDN settings for static assets
- Awareness of MySQL master/slave replication, including distributing reads and implementing a read-only mode in order to cope with the write master being unavailable
- Alternate search plugins

## LICENSE

[GNU General Public License v2](http://opensource.org/licenses/gpl-2.0.php)
