Change Log
----------

After v1.15
===========
- Added Xoshiro256** and Xoshiro512**, the preferred generators of this class
- Fixed bug in `jump` method of Random123 generators which did nto specify a default value



v1.15
=====
- Synced empty choice changes
- Synced upstream docstring changes
- Synced upstream changes in permutation
- Synced upstream doc fixes
- Added absolute_import to avoid import noise on Python 2.7
- Add legacy generator which allows NumPy replication
- Improve type handling of integers
- Switch to array-fillers for 0 parameter distribution to improve performance
- Small changes to build on manylinux
- Build wheels using multibuild
