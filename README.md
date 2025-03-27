# Awesome Rails With Postgres

ActiveRecord and Postgres do a lot. These gems help them to do much more together.

## Table of Contents

- [Gems](#gems)
- [Books](#books)

## Gems

### Performance Optimization

- [Alba](https://github.com/okuramasafumi/alba) – JSON serialization at warp speed
- [N+1 Control](https://github.com/palkan/n_plus_one_control) – Test for N+1 queries before they hit prod
- [bullet](https://github.com/flyerhzm/bullet) – Helps to find N+1 queries
- [prosopite](https://github.com/charkost/prosopite) – Helps to find N+1 queries
- [Columns Trace](https://github.com/fatkodima/columns_trace) – Know which columns actually get used
- [Goldiloader](https://github.com/salsify/goldiloader) – Automatic eager loading so you don’t have to
- [Fast Count](https://github.com/fatkodima/fast_count) – COUNT(*) but without the existential crisis
- [occams-record](https://github.com/jhollinger/occams-record) – Accelerates ActiveRecord with 3x-5x faster queries, reduced memory usage, and enhanced SQL features
- [postgresql_cursor](https://github.com/afair/postgresql_cursor) – Efficiently paginate through large datasets using Postgres cursors
- [Rails PG Extras](https://github.com/pawurb/rails-pg-extras) – EXPLAIN ANALYZE without the headaches
- [ActiveRecord Analyze](https://github.com/pawurb/activerecord-analyze) – EXPLAIN ANALYZE, but make it easy
- [Passive Columns](https://github.com/headmandev/passive_columns) – Keep unused columns from slowing you down
- [geared_pagination](https://github.com/basecamp/geared_pagination) – Simple, performance-focused pagination for large datasets
- [pagy](https://github.com/ddnexus/pagy) – The fastest pagination gem for Ruby on Rails
- [Isolator](https://github.com/palkan/isolator) – Detect non-atomic interactions within DB transactions

### Query Enhancement

- [Hightop](https://github.com/ankane/hightop) – GROUP BY, but make it fast
- [Groupdate](https://github.com/ankane/groupdate) – Time-based queries without the pain
- [Rollup](https://github.com/ankane/rollup) – Incrementally aggregate data in Postgres for fast reporting
- [Neighbor](https://github.com/ankane/neighbor) – Fast nearest-neighbor search, ActiveRecord style
- [ActiveRecordExtended](https://github.com/GeorgeKaraszi/ActiveRecordExtended) – Extend ActiveRecord with additional methods for common use cases, including querying and relation handling

### Soft Deletes and Versioning

- [Discard](https://github.com/jhawthorn/discard) – Soft deletes done right
- [logidze](https://github.com/palkan/logidze) – Maintain an immutable history of ActiveRecord models with ease
- [audited](https://github.com/collectiveidea/audited) – Track changes to ActiveRecord models and maintain a history of data modifications
- [paper_trail](https://github.com/paper-trail-gem/paper_trail) – Track changes to your ActiveRecord models and keep a history of all updates, deletes, and restores
- [paranoia](https://github.com/rubysherpas/paranoia) – Soft delete support for ActiveRecord models, ensuring deleted records can be recovered

### Multi-Tenancy

- [acts_as_tenant](https://github.com/ErwinM/acts_as_tenant) – Multi-tenancy support for Rails applications, simplifying tenant scoping

### Full-text Search

- [pg_search](https://github.com/Casecommons/pg_search) – Full-text search with Postgres for Rails applications
- [textacular](https://github.com/textacular/textacular) – Powerful text search for Postgres in Rails, with support for full-text and trigram search

### Database Structure and Schema Management

- [Scenic](https://github.com/scenic-views/scenic) – Views aren't just for frontend devs
- [fx](https://github.com/teoljungberg/fx) – Adds methods to ActiveRecord::Migration to create and manage database functions and triggers in Rails
- [ActiveRecord Postgres Enum](https://github.com/bibendi/-activerecord-postgres_enum) – Native Postgres enums without the hassle
- [Strong Migrations](https://github.com/ankane/strong_migrations) – Deploy without breaking literally everything
- [Online Migrations](https://github.com/fatkodima/online_migrations) – Migrate without downtime
- [pg_ha_migrations](https://github.com/braintree/pg_ha_migrations) – Postgres migration tool for high availability and failover scenarios
- [The Schema Is](https://github.com/zverok/the_schema_is) – Keep your schema.rb in check
- [annotaterb](https://github.com/drwl/annotaterb) – Automatically annotate your Ruby files with file metadata, such as author or date
- [ActiveRecord PostGIS Adapter](https://github.com/rgeo/activerecord-postgis-adapter) – Spatial data, the Rails way
- [rgeo](https://github.com/rgeo/rgeo) – Geospatial data handling for Ruby on Rails with support for PostGIS and other spatial extensions
- [ActiveRecord TypedStore](https://github.com/byroot/activerecord-typedstore) – Strongly typed ActiveRecord

### Attributes Management

- [Measured](https://github.com/Shopify/measured) – Keep units in check before they break things
- [awesome_nested_set](https://github.com/collectiveidea/awesome_nested_set) – An easy-to-use gem for storing hierarchical data in ActiveRecord
- [store_model](https://github.com/DmitryTsepelev/store_model) – Persist attributes on models as a serialized data column while keeping ActiveRecord’s features intact
- [ranked-model](https://github.com/brendon/ranked-model) – Easily manage ranked records with ActiveRecord
- [store_attribute](https://github.com/palkan/store_attribute) – Store model attributes in the database in a more structured way
- [acts-as-taggable-on](https://github.com/mbleigh/acts-as-taggable-on) – Add tagging functionality to any ActiveRecord model with ease

### Caching and Indexing

- [Blind Index](https://github.com/ankane/blind_index) – Encrypt data without losing searchability
- [wt_activerecord_index_spy](https://github.com/WeTransfer/wt_activerecord_index_spy) – Identify indexes that are never used
- [Counter Culture](https://github.com/magnusvk/counter_culture) – Stop recalculating counters like it's 2010
- [Identity Cache](https://github.com/Shopify/identity_cache) – Caching, but the Shopify way

### Database Integrity and Data Consistency

- [Database Consistency](https://github.com/djezzzl/database_consistency) – Finds schema & data issues before they find you
- [Active Record Doctor](https://github.com/gregnavis/active_record_doctor) – Your schema needs a checkup
- [activerecord-clean-db-structure](https://github.com/lfittl/activerecord-clean-db-structure) – Keep your schema clean

### Bulk Operations

- [ActiveRecord Import](https://github.com/zdennis/activerecord-import) – Bulk inserts that fly
- [postgres-copy](https://github.com/diogob/postgres-copy) – Fast bulk data import/export for Postgres

### Data Management

- [pgsync](https://github.com/ankane/pgsync) – Synchronize Postgres databases with ease, ideal for staging/production sync
- [evil-seed](https://github.com/evilmartians/evil-seed) – Generate realistic, yet safe, dummy data for testing and development
- [Maintenance Tasks](https://github.com/Shopify/maintenance_tasks) – Simplifies data migration management

### Tools

- [pgcli-rails](https://github.com/mattbrictson/pgcli-rails) – A better Postgres console for Rails
- [pghero](https://github.com/ankane/pghero) – Postgres performance insights

## Books

- [High Performance PostgreSQL for Rails](https://pragprog.com/titles/aapsql/high-performance-postgresql-for-rails/)
- [Lift the Elephant](https://leanpub.com/lift-the-elephant)
