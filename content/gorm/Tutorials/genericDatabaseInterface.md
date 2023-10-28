+++
title = "Generic database interface sql.DB"
date = 2023-10-28T14:31:29+08:00
type = "docs"
description = ""
isCJKLanguage = true
draft = false

+++

[https://gorm.io/docs/generic_interface.html](https://gorm.io/docs/generic_interface.html)

GORM provides the method `DB` which returns a generic database interface [*sql.DB](https://pkg.go.dev/database/sql#DB) from the current `*gorm.DB`

```
// Get generic database object sql.DB to use its functions
sqlDB, err := db.DB()

// Ping
sqlDB.Ping()

// Close
sqlDB.Close()

// Returns database statistics
sqlDB.Stats()
```

> **NOTE** If the underlying database connection is not a `*sql.DB`, like in a transaction, it will returns error

## Connection Pool

```
// Get generic database object sql.DB to use its functions
sqlDB, err := db.DB()

// SetMaxIdleConns sets the maximum number of connections in the idle connection pool.
sqlDB.SetMaxIdleConns(10)

// SetMaxOpenConns sets the maximum number of open connections to the database.
sqlDB.SetMaxOpenConns(100)

// SetConnMaxLifetime sets the maximum amount of time a connection may be reused.
sqlDB.SetConnMaxLifetime(time.Hour)
```