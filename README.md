# Awesome Rails With Postgres

ActiveRecord and Postgres do a lot. These gems help them to do even more.

## Table of Contents

- [Gems](#gems)
- [Books](#books)

## Gems

### Performance Optimization

- Alba – JSON serialization at warp speed → https://github.com/okuramasafumi/alba
- N+1 Control – Test for N+1 queries before they hit prod → https://github.com/palkan/n_plus_one_control
- bullet – Helps to find N+1 queries → https://github.com/flyerhzm/bullet
- prosopite – Helps to find N+1 queries → https://github.com/charkost/prosopite
- Columns Trace – Know which columns actually get used → https://github.com/fatkodima/columns_trace
- Goldiloader – Automatic eager loading so you don’t have to → https://github.com/salsify/goldiloader
- Fast Count – COUNT(*) but without the existential crisis → https://github.com/fatkodima/fast_count
- occams-record – Accelerates ActiveRecord with 3x-5x faster queries, reduced memory usage, and enhanced SQL features → https://github.com/jhollinger/occams-record
- postgresql_cursor – Efficiently paginate through large datasets using Postgres cursors → https://github.com/afair/postgresql_cursor
- Rails PG Extras – EXPLAIN ANALYZE without the headaches → https://github.com/pawurb/rails-pg-extras
- ActiveRecord Analyze – EXPLAIN ANALYZE, but make it easy → https://github.com/pawurb/activerecord-analyze
- Passive Columns – Keep unused columns from slowing you down → https://github.com/headmandev/passive_columns
- geared_pagination – Simple, performance-focused pagination for large datasets → https://github.com/basecamp/geared_pagination
- pagy – The fastest pagination gem for Ruby on Rails → https://github.com/ddnexus/pagy
- Isolator – Detect non-atomic interactions within DB transactions → https://github.com/palkan/isolator

### Query Enhancement

- Hightop – GROUP BY, but make it fast → https://github.com/ankane/hightop
- Groupdate – Time-based queries without the pain → https://github.com/ankane/groupdate
- Rollup – Incrementally aggregate data in Postgres for fast reporting → https://github.com/ankane/rollup
- Neighbor – Fast nearest-neighbor search, ActiveRecord style → https://github.com/ankane/neighbor
- ActiveRecordExtended – Extend ActiveRecord with additional methods for common use cases, including querying and relation handling → https://github.com/GeorgeKaraszi/ActiveRecordExtended

### Soft Deletes and Versioning

- Discard – Soft deletes done right → https://github.com/jhawthorn/discard
- logidze – Maintain an immutable history of ActiveRecord models with ease → https://github.com/palkan/logidze
- audited – Track changes to ActiveRecord models and maintain a history of data modifications → https://github.com/collectiveidea/audited
- paper_trail – Track changes to your ActiveRecord models and keep a history of all updates, deletes, and restores → https://github.com/paper-trail-gem/paper_trail
- paranoia – Soft delete support for ActiveRecord models, ensuring deleted records can be recovered → https://github.com/rubysherpas/paranoia

### Multi-Tenancy

- acts_as_tenant – Multi-tenancy support for Rails applications, simplifying tenant scoping → https://github.com/ErwinM/acts_as_tenant

### Full-text Search

- pg_search – Full-text search with Postgres for Rails applications → https://github.com/Casecommons/pg_search
- textacular – Powerful text search for Postgres in Rails, with support for full-text and trigram search → https://github.com/textacular/textacular

### Database Structure and Schema Management

- Scenic – Views aren't just for frontend devs → https://github.com/scenic-views/scenic
- fx – Adds methods to ActiveRecord::Migration to create and manage database functions and triggers in Rails → https://github.com/teoljungberg/fx
- ActiveRecord Postgres Enum – Native Postgres enums without the hassle → https://github.com/bibendi/- activerecord-postgres_enum
- Strong Migrations – Deploy without breaking literally everything → https://github.com/ankane/strong_migrations
- Online Migrations – Migrate without downtime → https://github.com/fatkodima/online_migrations
- pg_ha_migrations – Postgres migration tool for high availability and failover scenarios → https://github.com/braintree/pg_ha_migrations
- The Schema Is – Keep your schema.rb in check → https://github.com/zverok/the_schema_is
- annotaterb – Automatically annotate your Ruby files with file metadata, such as author or date → https://github.com/drwl/annotaterb
- ActiveRecord PostGIS Adapter – Spatial data, the Rails way → https://github.com/rgeo/activerecord-postgis-adapter
- rgeo – Geospatial data handling for Ruby on Rails with support for PostGIS and other spatial extensions → https://github.com/rgeo/rgeo
- ActiveRecord TypedStore – Strongly typed ActiveRecord → https://github.com/byroot/activerecord-typedstore

### Attributes Management

- Measured – Keep units in check before they break things → https://github.com/Shopify/measured
- awesome_nested_set – An easy-to-use gem for storing hierarchical data in ActiveRecord → https://github.com/collectiveidea/awesome_nested_set
- store_model – Persist attributes on models as a serialized data column while keeping ActiveRecord’s features intact → https://github.com/DmitryTsepelev/store_model
- ranked-model – Easily manage ranked records with ActiveRecord → https://github.com/brendon/ranked-model
- store_attribute – Store model attributes in the database in a more structured way → https://github.com/palkan/store_attribute
- acts-as-taggable-on – Add tagging functionality to any ActiveRecord model with ease → https://github.com/mbleigh/acts-as-taggable-on

### Caching and Indexing

- Blind Index – Encrypt data without losing searchability → https://github.com/ankane/blind_index
- wt_activerecord_index_spy – Identify indexes that are never used → https://github.com/WeTransfer/wt_activerecord_index_spy
- Counter Culture – Stop recalculating counters like it's 2010 → https://github.com/magnusvk/counter_culture
- Identity Cache – Caching, but the Shopify way → https://github.com/Shopify/identity_cache

### Database Integrity and Data Consistency

- Database Consistency – Finds schema & data issues before they find you → https://github.com/djezzzl/database_consistency
- Active Record Doctor – Your schema needs a checkup → https://github.com/gregnavis/active_record_doctor
- activerecord-clean-db-structure – Keep your schema clean → https://github.com/lfittl/activerecord-clean-db-structure

### Bulk Operations

- ActiveRecord Import – Bulk inserts that fly → https://github.com/zdennis/activerecord-import
- postgres-copy – Fast bulk data import/export for Postgres → https://github.com/diogob/postgres-copy

### Data Management

- pgsync – Synchronize Postgres databases with ease, ideal for staging/production sync → https://github.com/ankane/pgsync
- evil-seed – Generate realistic, yet safe, dummy data for testing and development → https://github.com/evilmartians/evil-seed
- Maintenance Tasks - Simplifies data migration management → https://github.com/Shopify/maintenance_tasks

### Tools

- pgcli-rails – A better Postgres console for Rails → https://github.com/mattbrictson/pgcli-rails
- pghero – Postgres performance insights → https://github.com/ankane/pghero

## Books

- [High Performance PostgreSQL for Rails](https://pragprog.com/titles/aapsql/high-performance-postgresql-for-rails/)
- [Lift the Elephant](https://leanpub.com/lift-the-elephant)
