---
{
  "title": "UseRoomInfoOptions interface",
  "linkToSource": "https://github.com/livekit/components-js/blob/main/packages/react/src/hooks/useRoomInfo.ts"
}
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# UseRoomInfoOptions interface

The `useRoomInfo` hook returns the name and metadata of the given `Room`<!-- -->.

**Signature:**

```typescript
export interface UseRoomInfoOptions
```

## Remarks

Needs to be called inside a `RoomContext` or by passing a `Room` instance.

## Usage

```tsx
const { name, metadata } = useRoomInfo();
```

{% partial file="p_usage.md" variables={exampleCount: 1} /%}

## Properties

| Property                                    | Type | Description  |
| ------------------------------------------- | ---- | ------------ |
| [room?](./react/useroominfooptions.room.md) | Room | _(Optional)_ |