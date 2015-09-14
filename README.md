GWT Maven Sample Project
=========================
Mirror of https://bitbucket.org/gardellajuanpablo/gwt-sample/wiki/Home

# Welcome

This is a gwt-sample project. Is helpfull to startup with gwt project that need JPA, Spring and Spring security. It is build using best practices.

# Features

A sample gwt project. It contains:

	* JPA 2.
	* gin.
	* gwt-dispatch. Handlers are spring managed beans.
	* jsr-330 in client and server side.
	* Spring.
	* Spring Security.
	* H2 database.
	* Build by maven.
	* Runnable by jetty (mvn jetty:deploy-war).
	* Autogenerate database by reading domain classes.

# Since 0.2.0

An HibernateFilter, an alternative to use DTOs or Gilead if your JPA provider is Hibernate.

# Install

	1. Download the sources.
	2. Execute: mvn package jetty:deploy-war
	3. Open http://localhost:8080/myapp-web
	4. Access with administrador/1234

# About

This sample is to contribute to GWT community. This sample is little contribution to this folks.