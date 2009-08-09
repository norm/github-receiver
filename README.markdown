github receiver
===============

A small daemon process to receive github post-receive hooks, and carry out
actions based upon them.

Used either as a stand-alone server process (using `HTTP::Server::Simple`)
run via the command-line, or as a CGI script.

Requirements:

*   perl 5.10
*   CPAN module [Modern::Perl][modern-perl]
*   CPAN module [HTTP::Server::Simple][http-server] (for the standalone 
    server mode)


[modern-perl]:http://search.cpan.org/dist/Modern-Perl/lib/Modern/Perl.pm
[http-server]:http://search.cpan.org/dist/HTTP-Server-Simple/lib/HTTP/Server/Simple.pm