# meshage
High performance shared memory messaging system.


There are some points to consdier:
* Having feature flag of whether to use hugepagse or not.
* Linking against libhugetlbfs.
* Setup docker containers to have shared-memory communication.
* Service registery point with RESTful API.
* Run on Ubuntu 18.04.

Configuration for:
* Hugepage size.


To read:
* How to enable huge page support in a Dockerfile
  * https://superuser.com/questions/1309438/how-to-enable-huge-page-support-in-a-dockerfile
