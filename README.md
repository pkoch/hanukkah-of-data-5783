# Hanukkah of Data 5783

https://hanukkah.bluebird.sh/

## Setup

```bash
dropdb noahs && createdb noahs && psql noahs < noahs.sql
```

## Example run

```bash
echo 1.sql | entr -c bash -c "psql noahs < 1.sql"
```

## Re-dump

```bash
pg_dump -Ox noahs > noahs.sql
```
