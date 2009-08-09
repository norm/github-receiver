github receiver
===============

A small script to receive github post-receive hooks, update checkouts and run
actions after github repositories are committed to. 

Used either as a stand-alone server process run from the command-line, or as a
CGI script from a normal web server.

Requirements:

*   perl 5.10
*   CPAN module [Modern::Perl][modern-perl]
*   CPAN module [HTTP::Server::Simple][http-server] (for the standalone 
    server mode)

Usage information of the script is available by running "perldoc receiver".

More information on the post-receive web hook is available 
[on github][post-receive].


[modern-perl]:http://search.cpan.org/dist/Modern-Perl/lib/Modern/Perl.pm
[http-server]:http://search.cpan.org/dist/HTTP-Server-Simple/lib/HTTP/Server/Simple.pm
[post-receive]:http://github.com/guides/post-receive-hooks
