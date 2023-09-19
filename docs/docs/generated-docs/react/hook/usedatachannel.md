---
{
  "title": "useDataChannel",
  "linkToSource": "https://github.com/livekit/components-js/blob/main/packages/react/src/hooks/useDataChannel.ts"
}
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# useDataChannel

The `useDataChannel` hook returns the ability to send and receive messages. By optionally passing a `topic`<!-- -->, you can narrow down which messages are returned in the messages array.

## Import

```typescript
import { useDataChannel } from "@livekit/components-react";
```

## Remarks

There is only one data channel. Passing a `topic` does not open a new data channel. It is only used to filter out messages with no or a different `topic`<!-- -->.

## Usage

```tsx
// Send messages to all participants via the 'chat' topic.
const { message, send } = useDataChannel("chat");
```

{% partial file="p_usage.md" variables={exampleCount: 1} /%}

## Properties

{% parameter name="topic" type="T" optional=false %}
{% /parameter %}

{% parameter name="onMessage" type="(msg: ReceivedDataMessage<T>) => void" optional=true %}
{% /parameter %}

## Returns

```typescript
UseDataChannelReturnType<T>;
```