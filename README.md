
# Multimedia;	video	streaming in eSystems

## Introduction
Over the last decade, the platform of eSystem have slowly imprinted into our everyday livelihood. A platform which allows accessibility of data, information, access and live feed update creates an easier approach to communication or media. The term multimedia is defined as a combination of information conveyed by text, audio, images or videos; with the common goal of distribution.

With the vast improvement of eSystems, integration of video processing, the transfer of live multimedia became possible and be used to access information in live sessions. This process has been used for video conferencing, live news, and social feeds. 

As for video streaming and distribution is used, little is known about the backhand of the process which involve in the technology. This paper looks into the backflow of video streaming.

## Background

### Video Compression
H.264 is the standard video coding system which combines block wise transformation coding and predictive coding to reduce the redundancy of a video. The coding adopts a hierarchical block structure of code unit, prediction unit and transform unit. The coding system divides the picture into slices of code unit tree which is then further divided to create the smallest possible code unit. The data is then process into a prediction mode and partition size to be stored/transfer. The predictive unit when called upon, then merge the code units or further advancement to the image if requested. (Yang, Lee, Shim & Jeon, 2013)

### Video Streaming
Multimedia applications have experienced a growth over the past decade with the change to High Definition, 4K resolution, SDTV and, more. Although the accomplishment with media application, video streaming services still face issues to guarantee high quality of service. Often the cost of bandwidth, delay and perhaps unstable servers. The problem often directed towards wireless hops which include interference, shadowing and mobility. Protocols are designed to react to situations of occurences such as Error resilience, video coding, forward error correction, rate-distortion  and error concealment

#### Error Resilience
In the H264 process, picture data is compressed and divided into semi smaller code units. Video streaming is the transfer of code units through transfer protocols; through this transfer, data may be lost due to decoding faulty or loss packets in the transfer. Error control techniques are called upon during the transmission error. While it is impossible to retrieve missing data, the technique uses low latencies to create stablility 

#### Video Coding 
Due to low badwith and bitstream, an alternative solution is to create a lower codeing efficiency. The result causes a lower compressed video and minimize the distortion of videos which may occur. The principle operates under the picture selection algorithm. 

### Forward Error Correction
Forward Error Correction is thee method of controlling possible error with data transmission. The process requires the sender to send a the packets twice and observes the instances and data from the packets. The protocol checks the different layers of bit-rate and combines the partition segments. 

### Rate-Distortion
The Rate-Distortion analyze video displacement similar to forward error correction base approach, but focus towards the individual packets that are missing. As data have timestamp and protocols, packets missing can be tracked. The mising packets are then requested back from the server end to obtain missing segmans. This approach looks for the important packets missing rather than resending the whole set of packets.

### Error Concealment
When the packets that is missing and cannot be avoid, a time allocation is limited to prevent stoppage. An error concealment is then called upon to create a visual artifact of assumed image. The temporal interpolation algorihtm artifacts of large displacements to estimate motion and image trajectories. 

