<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [HttpServiceSetup](./kibana-plugin-server.httpservicesetup.md) &gt; [registerOnPreResponse](./kibana-plugin-server.httpservicesetup.registeronpreresponse.md)

## HttpServiceSetup.registerOnPreResponse property

To define custom logic to perform for the server response.

<b>Signature:</b>

```typescript
registerOnPreResponse: (handler: OnPreResponseHandler) => void;
```

## Remarks

Doesn't provide the whole response object. Supports extending response with custom headers. See [OnPreResponseHandler](./kibana-plugin-server.onpreresponsehandler.md)<!-- -->.
