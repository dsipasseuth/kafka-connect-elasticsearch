.. _elasticsearch_connector_changelog:

Changelog
=========

Version 4.0.0
-------------

* `PR-122 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/122>`_ - Add argLine to surefire override configuration so we maintain the Jenkins features of the common pom.
* `PR-91 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/91>`_ - Drop invalid messages if needed
* `PR-88 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/88>`_ - Inherit from common pom

Version 3.3.1
-------------

* `PR-126 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/126>`_ - CC-1191: Added feature flag to control string-keyed map entry JSON serialization
* `PR-120 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/120>`_ - Add upstream project so build are triggered automatically
* `PR-117 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/117>`_ - CC-1096 Added ES error message when unable to create an index
* `PR-116 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/116>`_ - CC-1059 Changed ES connector to use exponential backoff with jitter
* `PR-105 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/105>`_ - Update quickstart to use Confluent CLI.

Version 3.3.0
-------------

* `PR-69 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/69>`_ - Fix map output for String keyed maps.
* `PR-83 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/83>`_ - ST-336: Move slf4j-simple into test scope so it is not pulled into the packaged version.

Version 3.2.2
-------------

* `PR-89 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/89>`_ - Increase flush timeout in BulkProcessorTest to make the test more reliable when the test server has other CPU load.

Version 3.2.1
-------------

No changes

Version 3.2.0
-------------

* `PR-34 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/34>`_ - CC-331: update config options docs
* `PR-47 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/47>`_ - Allow for multiple Elasticsearch HTTP URLs
* `PR-53 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/53>`_ - CC-392: Fix mapping existence check
* `PR-54 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/54>`_ - CC-393: don't use offset as document version when key.ignore=true
* `PR-49 <https://github.com/confluentinc/kafka-connect-elasticsearch/pull/49>`_ - Schema.Type.BYTES should map to 'binary' ES datatype
