# Contact Form Customer Mail

A lightweight Shopware 6 plugin that uses the email address submitted through
the standard contact form as the `Reply-To` address of the outgoing message.
Customer service can reply directly to the request without copying the
customer's address from the email body.

The configured sender address remains unchanged. No plugin configuration is
required.

## Requirements

- Shopware 6.7
- PHP 8.2, 8.3 or 8.4

## Installation

Download the installable ZIP from the
[latest GitHub release](https://github.com/aggrosoft/shopware-contact-form-customer-mail/releases/latest),
upload it through the Shopware Extension Manager, then install and activate
the extension.

The repository can also be added directly as an extension source through an
ExtensionMesh-compatible Shopware installation:

```text
https://github.com/aggrosoft/shopware-contact-form-customer-mail
```

## How it works

Before Shopware validates and sends a mail template, the plugin checks for an
email address in the standard contact-form data. When present, that address is
added as the message's `Reply-To` address.

## Support

Please report reproducible problems through
[GitHub Issues](https://github.com/aggrosoft/shopware-contact-form-customer-mail/issues).

## License

This project is licensed under the [MIT License](LICENSE).
