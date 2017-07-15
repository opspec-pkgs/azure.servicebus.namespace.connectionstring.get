# Problem statement
gets an azure servicebus namespace connection string

# Example usage

> note: in examples, VERSION represents a version of the azure.servicebus.namespace.connectionstring.get pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.servicebus.namespace.connectionstring.get#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.servicebus.namespace.connectionstring.get#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.servicebus.namespace.connectionstring.get#VERSION }
    inputs: 
      subscriptionId:
      loginId:
      loginSecret:
      loginTenantId:
      namespace:
      resourceGroup:
      # begin optional args
      authRule:
      authRuleKey:
      loginType:
      # end optional args
    outputs:
      connectionString:
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/azure.servicebus.namespace.connectionstring.get/issues)
