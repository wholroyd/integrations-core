# CHANGELOG - kafka_consumer

1.2.1 / Unreleased 
==================

### Changes

* [BUGFIX] Use instance key to retrieve cached kafka_client, See [#904][]

1.2.0 / 2017-11-21
==================

### Changes

* [FEATURE] Support collection of consumer offsets from Kafka, in addition to ZK. See [#654][]

1.1.0 / 2017-10-10
==================

### Changes

* [FEATURE] discovery of groups, topics and partitions. See [#633][] (Thanks [@jeffwidman][])
* [SANITY] set upper bound on number of contexts. Submit "broker available" metrics. See [#753][]
* [SANITY] Remove usage of `AgentCheck.read_config` (deprecated method). See [#733][]

1.0.2 / 2017-08-28
==================

### Changes

* [IMPROVEMENT] Bump Kazoo dependency to 2.4.0. See [#623][], thanks [@jeffwidman][]
* [IMPROVEMENT] Bump kafka-python to 1.3.4. See [#684][], thanks [@jeffwidman][]
* [IMPROVEMENT] Switch ZK example from string to list. See [#624][], thanks [@jeffwidman][]


1.0.1 / 2017-04-24
==================

### Changes

* [DEPENDENCY] bumping kafka-python to 0.3.3. See [#272][] (Thanks [@jeffwidman][])

1.0.0 / 2017-03-22
==================

### Changes

* [FEATURE] adds kafka_consumer integration.

<!--- The following link definition list is generated by PimpMyChangelog --->
[#272]: https://github.com/DataDog/integrations-core/issues/272
[#623]: https://github.com/DataDog/integrations-core/issues/623
[#624]: https://github.com/DataDog/integrations-core/issues/624
[#633]: https://github.com/DataDog/integrations-core/issues/633
[#654]: https://github.com/DataDog/integrations-core/issues/654
[#684]: https://github.com/DataDog/integrations-core/issues/684
[#733]: https://github.com/DataDog/integrations-core/issues/733
[#753]: https://github.com/DataDog/integrations-core/issues/753
[#904]: https://github.com/DataDog/integrations-core/issues/904
[@jeffwidman]: https://github.com/jeffwidman