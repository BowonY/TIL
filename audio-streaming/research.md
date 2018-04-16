# Building an Audio Streaming Server
## What do I need?
10 Raspberry Pis are sending audio data recorded in real-time to a server. Users should be able to play the sound through a browser.

## Real-time streaming server
* RTMP (Real-time messaging protocol):
Twitch is using RTMP to get video from broadcaster. The audio stream is sent through HTTP Live Streaming to the viewers. But it requires Flash!
* WebSocket: 
WebSocket is more for bi-directional signaling.
* WebRTC:
WebRTC is a good fit for multimedia streaming. So I chose WebRTC :D

## WebRTC tutorial resources
1. https://webrtc.ventures/2017/07/webrtc-tutorials/
2. https://github.com/webrtc/samples
3. https://www.tutorialspoint.com/webrtc/index.htm
