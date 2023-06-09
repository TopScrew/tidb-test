# Commands to trigger ci pipeline

## Guide

ci pipeline will be triggered when your comment on pull request matched command. But we have some task that will be triggered manually.

## Commands

| ci pipeline                              | Commands                                                        | 
| ---------------------------------------- |-----------------------------------------------------------------|
| tidb_ghpr_coverage                       | /run-coverage                                                   |
| tidb_ghpr_build_arm64                    | /run-build-arm64 comment=true                                   |
| tidb_ghpr_common_test                    | /run-common-test<br />/run-integration-tests                    |
| tidb_ghpr_integration_br_test            | /run-integration-br-test<br />/run-integration-tests            |
| tidb_ghpr_integration_campatibility_test | /run-integration-compatibility-test<br />/run-integration-tests |
| tidb_ghpr_integration_common_test        | /run-integration-common-test<br />/run-integration-tests        |
| tidb_ghpr_integration_copr_test          | /run-integration-copr-test<br />/run-integration-tests          |
| tidb_ghpr_integration_ddl_test           | /run-integration-ddl-test<br />/run-integration-tests           |
| tidb_ghpr_monitor_test                   | /run-monitor-test                                               |
| tidb_ghpr_mybatis                        | /run-mybatis-test<br />/run-integration-tests                   |
| tidb_ghpr_sqllogic_test_1                | /run-sqllogic-test<br />/run-integration-tests                  |
| tidb_ghpr_sqllogic_test_2                | /run-sqllogic-test<br />/run-integration-tests                  |
| tidb_ghpr_tics_test                      | /run-tics-test<br />/run-integration-tests                      |
| tidb_ghpr_unit_test                      | /run-unit-test<br />/run-all-tests<br />/merge                  |

