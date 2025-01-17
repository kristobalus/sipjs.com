<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [SimpleUser](./sip.js.simpleuser.md) &gt; [hangup](./sip.js.simpleuser.hangup.md)

## SimpleUser.hangup() method

Hangup a call.

<b>Signature:</b>

```typescript
hangup(): Promise<void>;
```
<b>Returns:</b>

Promise&lt;void&gt;

## Remarks

Send a BYE request, CANCEL request or reject response to end the current Session. Resolves when the request/response is sent, otherwise rejects. Use `onCallTerminated` delegate method to determine if and when call is ended.

