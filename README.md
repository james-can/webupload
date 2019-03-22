Code currently doesn't run as is, I removed my aws keys and domain names.  A video demoing the app can be found here: 

https://youtu.be/xRVeM-Enz8k


This app allowed our clients to upload their own 360 videos, using the AWS JavaScript sdk, which transcoded them to m3u8 format, extracting info and posting a link to the url in a google sheet. It also generated a thumbnail, allowing the client to choose from 8 different thumbnails, uploading only the one they choose, while also overlaying text as a caption. The mobile VR app would then download JSON from s3 which contained information about the relevant m3u8 which should be streamed.
