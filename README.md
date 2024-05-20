# WildFly/JBoss pipeline Example

## This is skill showcase repository

Full automation of the cycle of delivery of project artifacts, deployment, management of the JBoss / Wildfly cluster written in pure Groovy without any JBoss / Wildfly plugins for Jenkins.

Implemented:
 * Using JBOSS Management API.
 * Digest authorization in the JBoss Managemet API and all basic cluster management operations (start/stop/deploy/etc...).
 * Receiving artifacts from Nexus and Gitlab.
 * Binary loading of artifacts via JBoss Managemet API
 * Calling related helper services to inject Drools code.
 * Telegram notifications.

## v3.1.1

Added DRL for PROD env.

## v3.1.0

Some improvements and code cleanup.

## v3.0.0

GITLAB Client implemented.

DRL Injector added.

## v2.0.0

PROD env enabled

Added targetBuildVersion as Dropdown selector

Added suppressTelegramNotifications bool param

Added pipeline version output
