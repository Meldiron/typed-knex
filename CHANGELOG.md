# Changelog


## 2.9.0
- Updated on clauses for joins:
    - Deprecated `.onColumns`.
    - Added `.on`, `andOn`, `orOn`, `onVal`, `andOnVal`, `orOnVal`.

## 2.8.1

- Add deprecation warning for `FlattenOption.noFlatten`.

## 2.8.0

-   Updated support for `Date` to also include nullable values.
-   Added support for array type in entities.

## 2.7.0

-   Added `getTableName` and `getColumnName`.
-   Added `keepFlat`.
-   Upgraded packages.
-   Rewritten some internal helper types.
-   Added support for `Date` type in entities.

## 2.6.0

-   Overloaded `orWhere` and `andWhere` as to also accept an operator.
-   Added `orWhereNull` and `orWhereNotNull`.

## 2.5.0

-   Added `innerJoinTableOnFunction`.
-   Overloaded `where` as to also accept an operator.

## 2.4.1

-   Fix: better handling of optional properties.

## 2.1.0

-   Added `selectQuery`.

## 2.0.0

Completely different interface, feels like I'm doing a Python 3.
