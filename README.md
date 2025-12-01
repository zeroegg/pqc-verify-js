# QLabs PQC Verify - JavaScript

**Status**: 🚧 Coming Soon (Beta: Q2 2025)

Client-side JavaScript library for verifying PQC signatures (browser & Node.js).

## Features

- ✅ Verify Dilithium3 signatures
- ✅ Verify SPHINCS+ signatures
- ✅ Zero dependencies
- ✅ Works in browser & Node.js

## Installation

```bash
npm install @qlabs/pqc-verify
```

## Usage

```javascript
import { verifySignature } from '@qlabs/pqc-verify';

const isValid = verifySignature({
  message: 'Hello world',
  signature: '0x...',
  publicKey: '0x...',
  algorithm: 'dilithium3'
});

console.log(isValid); // true or false
```

## Beta Access

👉 [Join the waitlist](https://api.qlabsai.com) for early access.

---

© 2025 QLabs. MIT License.
