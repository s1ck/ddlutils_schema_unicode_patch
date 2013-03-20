Patch for Apache DDLUtils
=========================

* add support for Unicode Datatypes in MSSQL Server
* add support for Table Schemas in MSSQLServer

Note
----

* this is currently just an untested patch to support another project based on DDLutils
* just tested with SQL Server 2012 and the AdventureWorks2012 database
* no support for UDT added
* no extra test cases!

Install
-------

* `svn co http://svn.apache.org/repos/asf/db/ddlutils/trunk ddlutils`
* `git clone git@github.com:s1ck/ddlutils_schema_unicode_patch.git patch`
* `cd ddlutils`
* `patch -p0 -i ../patch/ddlutils_schema_unicode_patch`
* `mvn clean install`

