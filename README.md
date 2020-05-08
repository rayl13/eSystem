
Student ID : 1390847    Name:  Raymond Lum

title: Multimedia; Video Streaming in eSystem 

wikipage: Auckland University of Technology Assignment 1

Course : eSystem Design and Development 

Course ID: INFS804

# Multimedia;	video	streaming in eSystems

## Introduction
Over the last decade, the platform of eSystem have slowly imprinted into our everyday livelihood. A platform which allows accessibility of data, information, access and live feed update creates an easier approach to communication or media. The term multimedia is defined as a combination of information conveyed by text, audio, images or videos; with the common goal of distribution.

With the vast improvement of eSystems, integration of video processing, the transfer of live multimedia became possible and be used to access information in live sessions. This process has been used for video conferencing, live news, and social feeds. 

As for video streaming and distribution is used, little is known about the backhand of the process which involve in the technology. This paper looks into the backflow of video streaming.

### Video Compression
H.264 is the standard video coding system which combines block wise transformation coding and predictive coding to reduce the redundancy of a video. The coding adopts a hierarchical block structure of code unit, prediction unit and transform unit. The coding system divides the picture into slices of code unit tree which is then further divided to create the smallest possible code unit. The data is then process into a prediction mode and partition size to be stored/transfer. The predictive unit when called upon, then merge the code units or further advancement to the image if requested. (Yang, Lee, Shim & Jeon, 2013)

### Video Streaming
Multimedia applications have experienced a growth over the past decade with the change to High Definition, 4K resolution, SDTV and, more. Although the accomplishment with media application, video streaming services still face issues to guarantee high quality of service. Often the cost of bandwidth, delay and perhaps unstable servers. The problem often directed towards wireless hops which include interference, shadowing and mobility. Protocols are designed to react to situations of occurences such as Error resilience, video coding, forward error correction, rate-distortion  and error concealment

#### Error Resilience
In the H264 process, picture data is compressed and divided into semi smaller code units. Video streaming is the transfer of code units through transfer protocols; through this transfer, data may be lost due to decoding faulty or loss packets in the transfer. Error control techniques are called upon during the transmission error. While it is impossible to retrieve missing data, the technique uses low latencies to create stablility 

#### Video Coding 
Due to low badwith and bitstream, an alternative solution is to create a lower codeing efficiency. The result causes a lower compressed video and minimize the distortion of videos which may occur. The principle operates under the picture selection algorithm. 

#### Forward Error Correction
Forward Error Correction is thee method of controlling possible error with data transmission. The process requires the sender to send a the packets twice and observes the instances and data from the packets. The protocol checks the different layers of bit-rate and combines the partition segments. 

#### Rate-Distortion
The Rate-Distortion analyze video displacement similar to forward error correction base approach, but focus towards the individual packets that are missing. As data have timestamp and protocols, packets missing can be tracked. The mising packets are then requested back from the server end to obtain missing segmans. This approach looks for the important packets missing rather than resending the whole set of packets.

#### Error Concealment
When the packets that is missing and cannot be avoid, a time allocation is limited to prevent stoppage. An error concealment is then called upon to create a visual artifact of assumed image. The temporal interpolation algorihtm artifacts of large displacements to estimate motion and image trajectories. 

## Video Compression Coding
#### Transformation Block
The first step of video image/coding is the division of image into small blocks. The blocks of pixels are then converted into frequency domain. This process is called the Discrete Cosine Transform. WDCT helps seperate mroe perceptible information from less perceptible information. 
#### Quantization
As the frequency domain varies and are real numbers, quanitization rounds the numbers to their closest integer. While high-frequency DCT that are close to zero will bet set to 0

#### Entropy Coding
Nonzero coefficients are encorded by an entropy coder. Zero coefficients are encorded with run-length encoding. The higher the frequency, the shorter code and vice versa. 
#### Decoding
The variable-length code are decoded back to the quantized cofficient. The value is then multipled by the appropriate quantizer step size to get the DCT coefficent. With the DCT coefficent, the value is put in the inverse DCT to get the value of the domain. 
#note: image will not be identical to orginal image due to lost of information in quantiziation
#### Motion Estimation and Compensation
The motion feature are used as the reference frame to predict the current frame. With the predicted new frame is close to the actually frame size, the coded data is less than the original. The process is repeated over each block and processed in a timestamp.

*Motion estimate is requires more computation resource hence, requires the highest activity in video process.*

## Conclusion
Multimedia operates cover multiple encryption compression of data to smaller bits. The bits are transfers and encryped before sending through various network protocol and packets transfer. During the transfer protocols, information may be lost, altered or stolen which causes visual delays. Delays often happen over the speed of multimedia process with limited information. Although internet bandwidth and traffic often are cause of delays, video processing and encryption may have effects on the video. 


