---
{
  "title": "VideoTrackProps interface",
  "linkToSource": "https://github.com/livekit/components-js/blob/main/packages/react/src/components/participant/VideoTrack.tsx"
}
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# VideoTrackProps interface

**Signature:**

```typescript
export interface VideoTrackProps extends React.HTMLAttributes<HTMLVideoElement>
```

**Extends:** React.HTMLAttributes&lt;HTMLVideoElement&gt;

{% partial file="p_usage.md" variables={exampleCount: 0} /%}

## Properties

| Property                                                                               | Type                                                                               | Description                                              |
| -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [manageSubscription?](./react/videotrackprops.managesubscription.md)                   | boolean                                                                            | _(Optional)_                                             |
| [name?](./react/videotrackprops.name.md)                                               | string                                                                             | _(Optional)_                                             |
| [onSubscriptionStatusChanged?](./react/videotrackprops.onsubscriptionstatuschanged.md) | (subscribed: boolean) =&gt; void                                                   | _(Optional)_                                             |
| [onTrackClick?](./react/videotrackprops.ontrackclick.md)                               | (evt: [ParticipantClickEvent](./core/participantclickevent.md)<!-- -->) =&gt; void | _(Optional)_                                             |
| [participant?](./react/videotrackprops.participant.md)                                 | Participant                                                                        | _(Optional)_                                             |
| [publication?](./react/videotrackprops.publication.md)                                 | TrackPublication                                                                   | _(Optional)_                                             |
| [source?](./react/videotrackprops.source.md)                                           | Track.Source                                                                       | _(Optional)_                                             |
| [trackRef?](./react/videotrackprops.trackref.md)                                       | [TrackReference](./core/trackreference.md)                                         | _(Optional)_ The track reference of the track to render. |