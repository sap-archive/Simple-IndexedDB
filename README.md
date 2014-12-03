Simple-IndexedDB
================

This API wraps the IndexedDB API and makes working with it much simpler.

How to use:

  The main code of the Simple-IndexedDB is in app/storageUtil.
  Just grab the StorageUtil.js and the StorageUtilException.js and you are ready to use the Simple-IndexedDB.

What else is in the project:

  doc: API documentation in HTML format.
  <Enter> report: Code coverage reports.
  tests: Tests.

  Clone the repository, install the bower.json and the package.json and run the Gruntfile.js.
  Once running the Gruntfile the following tasks run:
  
    ugkify for creating a min file.
    jshint for static code check.
    jsdoc - Creating the API docs.
    qunit- Running qunit tests and code coverage.
    karma: Running headless browser tests.
