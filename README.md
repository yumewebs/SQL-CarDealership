# SQL CAR DEALERSHIP

This is a structured database for a car dealership.
> Sorry but all the exercises are in Spanish

You can find it here [Database](https://github.com/yumewebs/SQL-concesionario/blob/main/ejercicio01.sql)

### ENGINE=InnoDB or MyISAM?
I have added `InnoDB` instead of `MyISAM`.

The main advantages of `InnoDB` are:

- Transaction support
- Locking records
- It allows us to have the ACID characteristics (Atomicity, Consistency, Isolation and Durability: Atomicity, Consistency, Isolation and Durability in Spanish), guaranteeing the integrity of our boards.
- It is likely that if our application makes high use of INSERT and UPDATE we will notice an increase in performance compared to MyISAM.

And those of MyISAM:

- Overall faster data recovery.
- Recommended for applications that dominate the SELECT statements before INSERT / UPDATE.
- Absence of atomicity characteristics since it does not have to do referential integrity checks, or lock the tables to perform the operations, this leads us, like the previous points, to a higher speed.

#### Do you still have doubts which motor is the one you need?
- Is your table going to receive INSERT, UPDATE and DELETE much longer than it will be queried? We recommend `InnoDB`
- Will you need to do full-text searches? Your engine must be `MyISAM`
- Do you prefer or require relational database design? Then you need `InnoDB`
- Is disk space or RAM a problem? Go with `MyISAM`

### EXTRA
I have added different activities, apart from the database, to modify and add things to the database

