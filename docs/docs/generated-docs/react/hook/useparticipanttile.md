---
{
  "title": "useParticipantTile",
  "linkToSource": "https://github.com/livekit/components-js/blob/main/packages/react/src/hooks/useParticipantTile.ts"
}
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# useParticipantTile

The `useParticipantTile` hook is used to implement the `ParticipantTile` and returns the props needed to render the tile.

## Import

```typescript
import { useParticipantTile } from "@livekit/components-react";
```

## Remarks

The returned props include many data attributes that are useful for CSS styling purposes because they indicate the state of the participant and the track. For example: `data-lk-audio-muted`<!-- -->, `data-lk-video-muted`<!-- -->, `data-lk-speaking`<!-- -->, `data-lk-local-participant`<!-- -->, `data-lk-source`<!-- -->, `data-lk-facing-mode`<!-- -->.

{% partial file="p_usage.md" variables={exampleCount: 0} /%}

## Properties

{% parameter name="htmlProps" type="React.HTMLAttributes<T>" optional=false %}
{% /parameter %}

{% parameter name="disableSpeakingIndicator" type="boolean" optional=true %}
{% /parameter %}

{% parameter name="onParticipantClick" type="(event: ParticipantClickEvent) => void" optional=true %}
{% /parameter %}

{% parameter name="trackRef" type="TrackReferenceOrPlaceholder" optional=true %}
The track reference to display.

{% /parameter %}

{% parameter name="participant" type="Participant" optional=true deprecated=true %}
{% callout type="caution" variation="compact" %}
This parameter will be removed in a future version use `trackRef` instead.

{% /callout %}
{% /parameter %}

{% parameter name="publication" type="TrackPublication" optional=true deprecated=true %}
{% callout type="caution" variation="compact" %}
This parameter will be removed in a future version use `trackRef` instead.

{% /callout %}
{% /parameter %}

{% parameter name="source" type="Track.Source" optional=true deprecated=true %}
{% callout type="caution" variation="compact" %}
This parameter will be removed in a future version use `trackRef` instead.

{% /callout %}
{% /parameter %}

## Returns

```typescript
{
  elementProps: React.HTMLAttributes<T>;
}
```