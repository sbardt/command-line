# Message Digest Commands

## HMAC & SHA-1

To create a hashed HMAC digest of a string using SHA-1 and a key:

```bash
$ echo -n "string" | openssl dgst -sha1 -hmac "key"
```

```bash
$ echo -n "string" | openssl sha1 -hmac "key"
```

{% hint style="info" %}
MAC: keyed Message Authentication Code
{% endhint %}

