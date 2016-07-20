# pack_upseaton
Shinken pack for monitoring Eaton/MGE UPS

Usage : make sure that libexec/check_snmp_mgeeaton_ups.pl is accessible by shinken, then declare host as follows :


```
define host{
        use             upseaton
        host_name       [UPS short name]
        alias           [UPS longer name]
        address         [IP address]
    }

```
