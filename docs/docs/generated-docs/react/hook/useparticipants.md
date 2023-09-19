---
{
  "title": "useParticipants",
  "linkToSource": "https://github.com/livekit/components-js/blob/main/packages/react/src/hooks/useParticipants.ts"
}
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# useParticipants

The `useParticipants` hook returns all participants (local and remote) of the current room.

## Import

```typescript
import { useParticipants } from "@livekit/components-react";
```

## Remarks

To optimize performance, you can use the `updateOnlyOn` property to decide on what `RoomEvents` the hook updates.

## Usage

```tsx
const participants = useParticipants();
<ParticipantLoop participants={participants}>
  <ParticipantName />
</ParticipantLoop>;
```

{% partial file="p_usage.md" variables={exampleCount: 1} /%}

## Properties

{% parameter name="options" type="UseParticipantsOptions" optional=true %}
{% /parameter %}

## Returns

```typescript
(import("livekit-client").RemoteParticipant | import("livekit-client").LocalParticipant)[]
```