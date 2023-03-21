# ArchivesSpace DST Patches

## Note

For use with ArchivesSpace 3.3.1 *ONLY*

These files have *not* been tested in a production environment. Use at your own risk.

Includes recompiled common.jar, backend.war and updated database migration script (migrate_db.rb)
with patches from https://github.com/archivesspace/archivesspace/pull/2963

## Use

Replace the files bundled with the ArchivesSpace 3.3.1 release in the following locations

```
/lib/common.jar
/scripts/rb/migrate_db.rb
/wars/backend.war
```

with the files included in this repository.
