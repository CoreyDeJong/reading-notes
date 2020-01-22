### The Past, Present, and Future of Local Storage for Web Applications”
- UserData allows web pages to store up to 64kb of data per domain, intranet sites can store 10 times.
- __Gears__ is an open source google browser plugin aimed at providing additional capabilities to browser
- __HTML5 Storage / Local Storage / DOM Storage__ is a way for web pages to store named key/value pairs locally.
- data is stored as a string, so you need to use ``parseInt() or parseFloat()`` to coerce your retrieved data into the expected JavaScript datatype.
- There are “databases” with “records,” and each record has a set number of “fields.” Each field has a specific datatype, which is defined when the database is created. You can select a subset of records, then enumerate them with a “cursor.” Changes to the object store are handled within “transactions.”