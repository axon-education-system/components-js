---
{
  "title": "TrackToggle",
  "linkToSource": "https://github.com/livekit/components-js/blob/main/packages/react/src/components/controls/TrackToggle.tsx"
}
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# TrackToggle

With the `TrackToggle` component it is possible to mute and unmute your camera and microphone. The component uses an html button element under the hood so you can treat it like a button.

## Import

```typescript
import { TrackToggle } from "@livekit/components-react";
```

## Usage

```tsx
<LiveKitRoom>
  <TrackToggle source={Track.Source.Microphone} />
  <TrackToggle source={Track.Source.Camera} />
</LiveKitRoom>
```

{% partial file="p_usage.md" variables={exampleCount: 1} /%}

## Properties

{% parameter name="source" type="T" optional=false %}
{% /parameter %}

{% parameter name="captureOptions" type="CaptureOptionsBySource<T>" optional=true %}
_(Optional)_

{% /parameter %}

{% parameter name="initialState" type="boolean" optional=true %}
_(Optional)_

{% /parameter %}

{% parameter name="onChange" type="(enabled: boolean) => void" optional=true %}
_(Optional)_

{% /parameter %}

{% parameter name="showIcon" type="boolean" optional=true %}
_(Optional)_

{% /parameter %}