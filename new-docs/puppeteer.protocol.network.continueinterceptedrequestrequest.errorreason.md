<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Network](./puppeteer.protocol.network.md) &gt; [ContinueInterceptedRequestRequest](./puppeteer.protocol.network.continueinterceptedrequestrequest.md) &gt; [errorReason](./puppeteer.protocol.network.continueinterceptedrequestrequest.errorreason.md)

## Protocol.Network.ContinueInterceptedRequestRequest.errorReason property

If set this causes the request to fail with the given reason. Passing `Aborted` for requests marked with `isNavigationRequest` also cancels the navigation. Must not be set in response to an authChallenge.

<b>Signature:</b>

```typescript
errorReason?: ErrorReason;
```
