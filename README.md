mp4box
======

python mongodb mp4box media file checker and analysis

Streaming Video wrapper checker. Used Python and Mp4Box to batch check the structure of the media wrapper. Fixes a problem with checking the integrity of 42TB of .mp4 files stored on CDN Net-storage. If the upload/download to the net storage is interrupted the wrapper of the file will have missing bytes that prevent FMS streaming server from calling the file. This only manifest itself when the wrapper structure is analyzed. QuickTme and VLC will still play the file locally. 
