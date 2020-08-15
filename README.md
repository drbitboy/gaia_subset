# Gaia Data Release 2 star catalog subset for testing


## 8862 stars; roughly 1 star out of each 64kstars from [Gaia stars with magnitude < 18]

### cf. https://github.com/drbitboy/Tycho2_SQLite_Rtree

#### Sub-directory gaia/

    python gaia.py buildsqlitedb --sqlitedb=gaia_subset/gaia_subset.sqlite3 --testfilestride=256 --teststride=256

