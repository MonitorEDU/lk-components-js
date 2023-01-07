<!--
!!!! Autogenerated File !!!!
This file was created by @livekit/components-docs-gen and should not be changed manually.
The contents of this file can be replaced at any time which would lead to the loss of all manual changes.
-->

# MediaDeviceMenu

The MediaDeviceMenu prefab component is a button that opens a menu that lists all media devices and allows the user to select them.

## Usage

```tsx
<LiveKitRoom>
  <MediaDeviceMenu />
</LiveKitRoom>
```

<!--USAGE_INSERT_MARKER-->


## Props

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| kind | `MediaDeviceKind` |  |  |
| initialSelection | `string` |  |  |
| onActiveDeviceChange | `((kind: MediaDeviceKind, deviceId: string) => void)` |  |  |
