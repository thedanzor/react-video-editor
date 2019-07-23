# React Video Editor

![React Video Editor](https://raw.githubusercontent.com/mrtrwhite/react-video-editor/master/screenshot.png)

A simple video editor with markers for a start and finish.

Listen to the onUpdate method for changes to the marker bounds.

```
<VideoEditor src="/path/to/file" preload={true} muted={false} onUpdate={this.onUpdate}  />
```