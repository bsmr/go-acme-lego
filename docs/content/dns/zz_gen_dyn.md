---
title: "Dyn"
date: 2019-03-03T16:39:46+01:00
draft: false
slug: dyn
---

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/dyn/dyn.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->

Since: v0.3.0

Configuration for [Dyn](https://dyn.com/).


<!--more-->

- Code: `dyn`

{{% notice note %}}
_Please contribute by adding a CLI example._
{{% /notice %}}




## Credentials

| Environment Variable Name | Description |
|-----------------------|-------------|
| `DYN_CUSTOMER_NAME` | Customer name |
| `DYN_PASSWORD` | Password |
| `DYN_USER_NAME` | User name |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here](/lego/dns/#configuration-and-credentials).


## Additional Configuration

| Environment Variable Name | Description |
|--------------------------------|-------------|
| `DYN_HTTP_TIMEOUT` | API request timeout |
| `DYN_POLLING_INTERVAL` | Time between DNS propagation check |
| `DYN_PROPAGATION_TIMEOUT` | Maximum waiting time for DNS propagation |
| `DYN_TTL` | The TTL of the TXT record used for the DNS challenge |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here](/lego/dns/#configuration-and-credentials).




## More information

- [API documentation](https://help.dyn.com/rest/)

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/dyn/dyn.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
