# Справочник по SQL

## Категории команд SQL
1. В языке SQL (Structure Query language) имеются несколько видов категорий команд:
1.2 DDL (Data Definition Language) (1)  
1.3 DML (Data Management Language) (2)  
1.4 DCL (Data Control Language) (3)  
1.5 TCL (Transaction Control Language) (4)
    { .annotate }   

    1.  Используются такие команды как (CREATE, DROP, RENAME, ALTER)
    2.  Используются такие команды как (SELECT, UPDATE, DELETE, EXPLAIN PLAN, CALL, LOCK)
    3.  Используются такие команды как (GRANT, REVOKE, DENY)
    4.  Используются такие команды как (COMMIT, ROLLBACK, BEGIN)



````mermaid

graph TD;
    SQL --> DDL	-..->id1[CREATE, DROP, RENAME, ALTER]
    SQL --> DML -..-> id2[SELECT, UPDATE, DELETE, EXPLAIN PLAN, CALL, LOCK]
    SQL --> DCL -..-> id3[GRANT, REVOKE, DENY]
    SQL --> TCL -..-> id4[COMMIT, ROLLBACK, BEGIN]
    click DML "../dml"
    click DDL "../ddl"
    click DCL "../dcl"
    click TCL "../tcl"
````
