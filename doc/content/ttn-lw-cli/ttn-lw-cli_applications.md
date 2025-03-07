---
title: "ttn-lw-cli applications"
slug: ttn-lw-cli_applications
---

## ttn-lw-cli applications

Application commands

### Options

```
  -h, --help   help for applications
```

### Options inherited from parent commands

```
      --allow-unknown-hosts                             Allow sending credentials to unknown hosts
      --application-server-enabled                      Application Server enabled (default true)
      --application-server-grpc-address string          Application Server address (default "localhost:8884")
      --ca string                                       CA certificate file
  -c, --config strings                                  Location of the config files (default [.ttn-lw-cli.yml,$HOME/.ttn-lw-cli.yml,$HOME/.config/.ttn-lw-cli.yml])
      --credentials-id string                           Credentials ID (if using multiple configurations)
      --device-claiming-server-grpc-address string      Device Claiming Server address (default "localhost:8884")
      --device-template-converter-grpc-address string   Device Template Converter address (default "localhost:8884")
      --dump-requests                                   When log level is set to debug, also dump request payload as JSON
      --experimental.features strings                   Experimental features to activate
      --gateway-server-enabled                          Gateway Server enabled (default true)
      --gateway-server-grpc-address string              Gateway Server address (default "localhost:8884")
      --identity-server-grpc-address string             Identity Server address (default "localhost:8884")
      --input-format string                             Input format (default "json")
      --insecure                                        Connect without TLS
      --join-server-enabled                             Join Server enabled (default true)
      --join-server-grpc-address string                 Join Server address (default "localhost:8884")
      --log.format string                               Log format to write (console, json) (default "console")
      --log.level string                                The minimum level log messages must have to be shown (default "info")
      --network-server-enabled                          Network Server enabled (default true)
      --network-server-grpc-address string              Network Server address (default "localhost:8884")
      --oauth-server-address string                     OAuth Server address (default "https://localhost/oauth")
      --output-format string                            Output format (default "json")
      --packet-broker-agent-grpc-address string         Packet Broker Agent address (default "localhost:8884")
      --qr-code-generator-grpc-address string           QR Code Generator address (default "localhost:8884")
      --retry.default-timeout duration                  Default timeout between retry attempts (default 100ms)
      --retry.enable-metadata                           Use request response metadata to dynamically calculate timeout between retry attempts (default true)
      --retry.jitter float                              Fraction that creates a deviation of the timeout used between retry attempts
      --retry.max uint                                  Maximum amount of times that a request can be reattempted
      --skip-version-check                              Do not perform version checks
      --telemetry.enable                                Enables telemetry for CLI (default true)
      --telemetry.target string                         Target to which the information will be sent to (default "https://telemetry.thethingsstack.io/collect")
```

### SEE ALSO

* [ttn-lw-cli]({{< relref "ttn-lw-cli" >}})	 - The Things Industries Command-line Interface
* [ttn-lw-cli applications activation-settings]({{< relref "ttn-lw-cli_applications_activation-settings" >}})	 - Application activation settings commands
* [ttn-lw-cli applications api-keys]({{< relref "ttn-lw-cli_applications_api-keys" >}})	 - Manage application API keys
* [ttn-lw-cli applications collaborators]({{< relref "ttn-lw-cli_applications_collaborators" >}})	 - Manage application collaborators
* [ttn-lw-cli applications contact-info]({{< relref "ttn-lw-cli_applications_contact-info" >}})	 - Manage application contact info (DEPRECATED. Instead, use administrative_contact and technical_contact fields of application)
* [ttn-lw-cli applications create]({{< relref "ttn-lw-cli_applications_create" >}})	 - Create an application
* [ttn-lw-cli applications delete]({{< relref "ttn-lw-cli_applications_delete" >}})	 - Delete an application
* [ttn-lw-cli applications get]({{< relref "ttn-lw-cli_applications_get" >}})	 - Get an application
* [ttn-lw-cli applications issue-dev-eui]({{< relref "ttn-lw-cli_applications_issue-dev-eui" >}})	 - Issue DevEUI for application
* [ttn-lw-cli applications link]({{< relref "ttn-lw-cli_applications_link" >}})	 - Application link commands
* [ttn-lw-cli applications list]({{< relref "ttn-lw-cli_applications_list" >}})	 - List applications
* [ttn-lw-cli applications packages]({{< relref "ttn-lw-cli_applications_packages" >}})	 - Application packages commands
* [ttn-lw-cli applications pubsubs]({{< relref "ttn-lw-cli_applications_pubsubs" >}})	 - Application pub/sub commands
* [ttn-lw-cli applications purge]({{< relref "ttn-lw-cli_applications_purge" >}})	 - Purge an application
* [ttn-lw-cli applications restore]({{< relref "ttn-lw-cli_applications_restore" >}})	 - Restore an application
* [ttn-lw-cli applications rights]({{< relref "ttn-lw-cli_applications_rights" >}})	 - List the rights to an application
* [ttn-lw-cli applications search]({{< relref "ttn-lw-cli_applications_search" >}})	 - Search for applications
* [ttn-lw-cli applications set]({{< relref "ttn-lw-cli_applications_set" >}})	 - Set properties of an application
* [ttn-lw-cli applications storage]({{< relref "ttn-lw-cli_applications_storage" >}})	 - Storage Integration
* [ttn-lw-cli applications subscribe]({{< relref "ttn-lw-cli_applications_subscribe" >}})	 - Subscribe to application uplink
* [ttn-lw-cli applications webhooks]({{< relref "ttn-lw-cli_applications_webhooks" >}})	 - Application webhooks commands

