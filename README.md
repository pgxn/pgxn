PGXN
===

[PGXN](http://www.pgxn.org/), the PostgreSQL Extention network, is a central
distribution system for open-source PostgreSQL extension libraries. It
consists of four parts:

* A [network of mirrors](http://pgxn.org/mirroring.html) for the geographic
  distribution of extension packages. The master mirror is
  [here](http://master.pgxn.org/).

* [PGXN Manager](http://manager.pgxn.org/) is a web application via which
  users can upload packages for distribution on the network
  ([source](https://github.com/theory/pgxn-manager)).

* [PGXN API](http://api.pgxn.org/) is a web application that syncs itself
  to a PGXN mirror and provides a RESTFUL interface for use by PGXN clients
  ([source](https://github.com/theory/pgxn-api)).

* [PGXN](http://pgxn.org/) is the main web site for the network, and client to
  the API. It includes pages describing all the contents of the network,
  including all released distributions and their documentation, and is fully
  searchable. It is currently under heavy development
  ([source](https://github.com/theory/pgxn-site)).

* A command-line client for installing packages distributed via the network.
  Development of this piecs has not yet begun.

Project Status
--------------

The main site is currently under heavy development, but is expected to be
launched by the end of March, 2011. Until that time, the early fundraising
pages of the site, stored in [this
repository](https://github.com/theory/pgxn)), continue to be served. Once the
new site goes live, this repository will no longer be worked on, but this page
will remain as a pointer to all of the sub-projects that encompass the whole
of PGXN.

Who’s Doing This?
-----------------

[I am](http://justatheory.com/ "Just a Theory"). I’m David Wheeler, inveterate
Perl and PostgreSQL hacker. I love the
[extensibility](http://www.postgresql.org/docs/current/static/extend.html) of
PostgreSQL and have long been a fan of [CPAN](http://www.cpan.org/), the Perl
community’s distributed collection of Perl software and documentation. But
PostgreSQL’s extensibility is not well-known, and it’s difficult to find the
extensions that do exist. I’d like to solve that problem. Care to help?
