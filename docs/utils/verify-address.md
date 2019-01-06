---
id: verify-address
title: verifyAddress
---

In the US, we validate addresses using [Smarty Streets](`https://smartystreets.com`). This cuts down on invalid addresses making their way to fulfillment at the warehouse.

Use [`verifyAddress`](https://github.com/birchbox/bernard_black/blob/develop/src/components/Addresses/verifyAddress.js) in a [`Form`](components/form.md) `onBeforeSubmit` to verify an address with Smarty Streets before submitting.
