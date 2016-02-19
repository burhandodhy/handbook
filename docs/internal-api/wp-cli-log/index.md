---
layout: default
title: WP_CLI::log()
---

<a href="/docs/internal-api/">Internal API</a> &raquo; Output

## WP_CLI::log()

Display informational message without prefix.

***

### Usage

    WP_CLI::log( $message )

<div>
<strong>$message</strong> (string) Message to write to STDOUT.<br />
</div>


***

### Notes

Message is written to STDOUT, or discarded when `--quiet` flag is supplied.


    # `wp cli update` lets user know of each step in the update process.
    WP_CLI::log( sprintf( 'Downloading from %s...', $download_url ) );
    



***

### Related

<ul>



<li><strong><a href="/docs/internal-api/wp-cli-utils-format-items/">WP_CLI\Utils\format_items()</a></strong> - Render a collection of items as an ASCII table, JSON, CSV, YAML, list of ids, or count.</li>


<li><strong><a href="/docs/internal-api/wp-cli-line/">WP_CLI::line()</a></strong> - Display informational message without prefix, and ignore `--quiet`.</li>


<li><strong><a href="/docs/internal-api/wp-cli-success/">WP_CLI::success()</a></strong> - Display success message prefixed with &quot;Success: &quot;.</li>


<li><strong><a href="/docs/internal-api/wp-cli-debug/">WP_CLI::debug()</a></strong> - Display debug message prefixed with &quot;Debug: &quot; when `--debug` is used.</li>


<li><strong><a href="/docs/internal-api/wp-cli-warning/">WP_CLI::warning()</a></strong> - Display warning message prefixed with &quot;Warning: &quot;.</li>


<li><strong><a href="/docs/internal-api/wp-cli-error/">WP_CLI::error()</a></strong> - Display error message prefixed with &quot;Error: &quot; and exit script.</li>



</ul>

