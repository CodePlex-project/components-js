<!--
!!!! Autogenerated File !!!!
This file was created by @livekit/components-docs-gen and should not be changed manually.
The contents of this file can be replaced at any time which would lead to the loss of all manual changes.
-->

# GridLayout

The GridLayout component displays the nested participants in a grid where every participants has the same size.

## Usage

```tsx
<LiveKitRoom>
  <GridLayout track={tracks} />
<LiveKitRoom>
```

<!--USAGE_INSERT_MARKER-->


## Props

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| tracks | `TrackReferenceOrPlaceholder[]` |  |  |
| updateOnlyOn | `RoomEvent[]` |  | To optimize performance, you can use the `updateOnlyOn` property to decide on what RoomEvents the hook updates. By default it updates on all relevant RoomEvents to keep the returned participants array up to date. The minimal set of non-overwriteable `RoomEvents` is: `[RoomEvent.ParticipantConnected, RoomEvent.ParticipantDisconnected, RoomEvent.ConnectionStateChanged]` |

