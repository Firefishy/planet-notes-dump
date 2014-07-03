planet-notes-dump
=================

A utility to dump OpenStreetMap notes from the database into an XML file for bulk use.

Installation
------------

On Ubuntu 12.04 LTS:

    # Install prerequisites for planet-notes-dump
    sudo apt-get install python-psycopg2 python-lxml

Running
-------

    # Execute the initial dump
    python dump.py --database openstreetmap --username foo notes_dump.xml

