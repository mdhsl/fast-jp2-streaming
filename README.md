# fast-jp2-streaming

Video of a server I developed allowing real-time streaming of satellite images in JP2 format.

The webservice supports the WMTS standard and uses Kakadu (with JAVA binding) for the decompression of JP2 image pieces and OpenCV (for warping + rendering in WMTS 256x256 pixels tile).

The WebService is in JAVA (Jetty Servlet). 

ps:The quality of the video has been degraded to respect the 10MB limit requested by Github

https://user-images.githubusercontent.com/6577027/128518277-c22b314e-3bc3-422d-acf0-c4f4c67380f6.mp4

