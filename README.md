sql-server-adapter-2000-friendly
================================
**USE THIS AT YOUR OWN RISK**

Merged the files modified by the [twshelton solution](https://github.com/twshelton/activerecord-sqlserver-adapter) with the current [sqlserver activerecord gem](https://github.com/rails-sqlserver/activerecord-sqlserver-adapter) for rails 3.2

The gem file and version compatible with this hack is:
activerecord-sqlserver-adapter (3.2.10)

**Installation:**

Download the gem activerecord-sqlserver-adapter (3.2.10), and then copy over the following files over the gem directory:

* lib/active_record/connection_adapters/sqlserver/database_statements.rb
* lib/active_record/connection_adapters/sqlserver/schema_statements.rb
* lib/active_record/connection_adapters/sqlserver_adapter.rb
* lib/arel/visitors/sqlserver.rb
