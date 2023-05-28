1. Select the GO configuration and install it on your device 

https://go.dev/dl/

2. Download source

$ git clone https://github.com/bogdanperley/WebRTC

3. CD to Directory 

$ cd WebRTС/

4. Create the binary file 

go build -ldflags "-s -w" -o rtsp2webrtc_amd64.exe

 5. Run

rtsp2webrtc_amd64.exe

6. Go to Browser

open web browser http://localhost:10001/stream/player/H264_AAC
