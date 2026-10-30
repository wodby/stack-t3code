# T3 Code application stack for Kubernetes on Wodby

Deploy T3 Code applications on Kubernetes with Wodby.

This repository defines the Wodby stack manifests and default service
composition for T3 Code.

<!-- wodby:generated:start -->

## Stack contract

- [T3 Code stack on Wodby](https://wodby.com/stacks/t3code)
- [Browse Wodby application stacks](https://wodby.com/stacks)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## Service definitions

- [T3 Code service](https://github.com/wodby/service-t3code)

## What's included

| Component / service | Default configuration |
| --- | --- |
| T3 Code<br>`t3code` | required; enabled by default |

Enabled optional services are selected by default but can be excluded when an
app is created. Disabled optional services are available but not selected by
default. Required services cannot be excluded.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->
