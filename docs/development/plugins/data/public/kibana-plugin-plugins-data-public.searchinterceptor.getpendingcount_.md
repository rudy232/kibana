<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-data-public](./kibana-plugin-plugins-data-public.md) &gt; [SearchInterceptor](./kibana-plugin-plugins-data-public.searchinterceptor.md) &gt; [getPendingCount$](./kibana-plugin-plugins-data-public.searchinterceptor.getpendingcount_.md)

## SearchInterceptor.getPendingCount$ property

Returns an `Observable` over the current number of pending searches. This could mean that one of the search requests is still in flight, or that it has only received partial responses.

<b>Signature:</b>

```typescript
getPendingCount$: () => Observable<number>;
```
