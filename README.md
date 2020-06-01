# wp-plugin-dist-diff

Quickly review a diff of two published versions of a WordPress plugin in the public WP plugin directory

## Usage

    wp-plugin-dist-diff plugin-slug old-version new-version

`plugin-slug` should be the slug of the target plugin as shown in the URL of `https://wordpress.org/plugins/plugin-slug`

For example, `wp-plugin-dist-diff redirection 4.7.2 4.8`

## Requirements

 * bash
 * hexdump
 * awk
 * unzip
 * curl
 * git (uses `git diff` for colourisation and easy recursive diffing)

