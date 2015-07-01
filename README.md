# wp-plugin-vulnerabilities
A standardized collection of WordPress plugin vulnerabilities.

The data for this has been extracted from the '[Plugin Vulnerabilities](https://wordpress.org/plugins/plugin-vulnerabilities/)' plugin
in the WordPress.org repository and stored in a standardised YAML format. These developers have provided all the original source data for this YAML, all we have
done is extract it from the PHP source code and stored it in YAML.

The Keys to the YAML structure are the WordPress.org plugin slugs and can be used to easily identify installed plugins using the plugins' directory name 
(this unfortunately isn't always reliable due to the nature of WordPress.org plugins).

Every attempt will be made to keep this up-to-date and in-line with the releases of the plugin.

Tags are the date at which the data has been imported from the plugin and to see how "up-to-date" it is, compare this with the "last updated" date
release of said plugin.

I wanted to work with the original developers on creating a standard data store for this,
[but my suggestion was rejected](https://wordpress.org/support/topic/centralrized-data-options) so I've forged ahead anyway. To help with this
project, please feel free to issue pull requests etc. and I will consider them all in due time.

Plans: Incorporate this in to the [WordPress Simple Firewall](https://wordpress.org/plugins/wp-simple-firewall/)

Service provided by [iControlWP](www.icontrolwp.com).

Last Updated: 2015-07-01