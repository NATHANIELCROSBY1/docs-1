---
title: Cryptography breaking changes
description: Lists cryptography-related breaking changes in .NET Core.
ms.date: 02/10/2020
---
# Cryptography breaking changes

The following breaking changes are documented on this page:

| Breaking change | Version introduced |
| - | :-: |
| [EnvelopedCms defaults to AES-256 encryption](#envelopedcms-defaults-to-aes-256-encryption) | 3.0 |
| [Minimum size for RSAOpenSsl key generation has increased](#minimum-size-for-rsaopenssl-key-generation-has-increased) | 3.0 |
| [.NET Core 3.0 prefers OpenSSL 1.1.x to OpenSSL 1.0.x](#net-core-30-prefers-openssl-11x-to-openssl-10x) | 3.0 |
| [Better argument validation in the Pkcs8PrivateKeyInfo constructor](#better-argument-validation-in-the-pkcs8privatekeyinfo-constructor) | 3.0 |
| [Boolean parameter of SignedCms.ComputeSignature is respected](#boolean-parameter-of-signedcmscomputesignature-is-respected) | 2.1 |

## .NET Core 3.0

[!INCLUDE[EnvelopedCms defaults to AES-256 encryption](~/includes/core-changes/cryptography/3.0/envelopedcms-defaults-to-aes256.md)]

***

[!INCLUDE[Minimum size for RSAOpenSsl key generation has increased](~/includes/core-changes/cryptography/3.0/minimum-rsaopenssl-key-size-change.md)]

***

[!INCLUDE[.NET Core 3.0 prefers OpenSSL 1.1.x to OpenSSL 1.0.x](~/includes/core-changes/cryptography/3.0/net-core-3-0-prefers-openssl-1-1-x.md)]

***

[!INCLUDE[Better argument validation in the Pkcs8PrivateKeyInfo constructor](~/includes/core-changes/cryptography/3.0/better-argument-validation-in-pkcs8privatekeyinfo-ctor.md)]

***

## .NET Core 2.1

[!INCLUDE [Boolean parameter of SignedCms.ComputeSignature is respected](~/includes/core-changes/cryptography/2.1/compute-signature-silent-parameter.md)]

***
