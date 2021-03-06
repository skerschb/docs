.. Only include this file on a page containing the section title
.. "Run MongoDB Community Edition"

MongoDB provides officially supported packages in their own repository. This
repository contains the following packages:

.. list-table::
   :header-rows: 1
   :widths: 25 75

   * - Package Name
     - Description

   * - ``{+package-name-org+}``
     - A ``metapackage`` that will automatically install
       the four component packages listed below.

   * - ``{+package-name-org+}-server``
     - Contains the :binary:`~bin.mongod` daemon and associated
       configuration and init scripts.

   * - ``{+package-name-org+}-mongos``
     - Contains the :binary:`~bin.mongos` daemon.

   * - ``{+package-name-org+}-shell``
     - Contains the :binary:`~bin.mongo` shell.

   * - ``{+package-name-org+}-tools``
     - Contains the following MongoDB tools: :binary:`~bin.mongoimport`
       :binary:`~bin.bsondump`, :binary:`~bin.mongodump`, :binary:`~bin.mongoexport`,
       :binary:`~bin.mongofiles`,
       :binary:`~bin.mongorestore`, :binary:`~bin.mongostat`,
       and :binary:`~bin.mongotop`.

The ``{+package-name-org+}-server`` package provides an initialization script
that starts :binary:`~bin.mongod` with the ``/etc/mongod.conf``
configuration file.

.. Links to the section in the including page having this title.

See `Run MongoDB Community Edition`_ for details on using this
initialization script.
