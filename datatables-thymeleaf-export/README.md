datatables-thymeleaf-export
=================================================================

A sample which shows how to export data using both DOM and AJAX sources, based on Spring3.

## Technology stack

 - Thymeleaf 2.1.4.RELEASE
 - Dandelion-Datatables 1.1.0
 - Jackson 1.9.13
 - Spring 3.2.10.RELEASE
 - Hibernate 4.3.5.Final / JPA 2.0
 - H2 database

## Features

 - __Data source type__: DOM + AJAX + server-side processing
 - Filter-based export (DOM sources)
 - Controller-based export (DOM and AJAX sources)
 - Customized column content
 - Customized export

## Running this sample

Using __Jetty__:

    mvn jetty:run


You can then access the sample here: [http://localhost:8080/export](http://localhost:8080/export)

## Bug/improvement

Please report it using the corresponding issue tracker: [https://github.com/dandelion/dandelion-datatables-samples/issues](https://github.com/dandelion/dandelion-datatables-samples/issues)


The [Dandelion team](http://dandelion.github.io/team/).
