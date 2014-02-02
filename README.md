# Motivation
I love [Pyramid](http://www.pylonsproject.org/projects/pyramid/about) as a Python web application framework for its simplicity and robustness but found going through the same setup process for every new project a hustle. It got in the way of my getting into the actual application's development. This is a scaffold of my common usage patterns that I've refined (and continue to refine) over time.

# Components
 - SQLAlchemy as the "ORM"
 - Hybrid routing, making use of both [Route Traversal](http://docs.pylonsproject.org/projects/pyramid/en/latest/narr/traversal.html) and [URL Dispatch](http://docs.pylonsproject.org/projects/pyramid/en/latest/narr/urldispatch.html)
 - [Alembic](https://bitbucket.org/zzzeek/alembic) for database schema migrations
 - [Colander](http://docs.pylonsproject.org/projects/colander/en/latest/) and [Deform](http://docs.pylonsproject.org/projects/deform/en/latest/) for form rendering and validation

# Installation
 1. ```
 pip install pyramid-webapp-scaffold
 ```

# Usage