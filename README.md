# NAME

Web::Library::jQuery - Distribution wrapper around jQuery

# SYNOPSIS

    my $library_manager = Web::Library->instance;
    $library_manager->mount_library({ name => 'jQuery' });

# DESCRIPTION

This is a distribution wrapper around jQuery. It enables you to include the
client-side library in multiple Web application projects with very little
effort. See [Web::Library](https://metacpan.org/module/Web::Library) for the general concept and how to use it with
[Catalyst](https://metacpan.org/module/Catalyst).

# LIBRARY VERSIONS

The following versions are available. For each version all included files are
listed. Files marked with an asterisk are included in that versions' asset
list - see [Web::Library](https://metacpan.org/module/Web::Library)'s `css_link_tags_for()` and `script_tags_for()`
methods for an explanation of the concept.

- Version 1.9.1

        * js/jquery.min.js
- Version 2.0.0 (the default)

        * js/jquery.min.js

# LIBRARY WEBSITE

jQuery can be found at [http://jquery.com/](http://jquery.com/).

# AUTHORS

The following person is the author of all the files provided in
this distribution EXCEPT jQuery files found in `share/`.

Marcel Gruenauer `<marcel@cpan.org>`, [http://marcelgruenauer.com](http://marcelgruenauer.com)

# COPYRIGHT AND LICENSE

jQuery is licensed under the [MIT license](https://jquery.org/license/).

The following copyright notice applies to all files provided in this
distribution EXCEPT jQuery files found in `share/`.

This software is copyright (c) 2013 by Marcel Gruenauer.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
