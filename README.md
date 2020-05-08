
Student ID : 1390847    Name:  Raymond Lum

title: Multimedia; Video Streaming in eSystem 

wikipage: Auckland University of Technology Assignment 1

Course : eSystem Design and Development 

Course ID: INFS804

## Introduction
Over the last decade, the platform of eSystem has slowly imprinted into our everyday livelihood. A platform that allows access to data, information,  live-feed, and creates an easier approach to communication or media. The term multimedia is defined as a combination of information conveyed by text, audio, images, or videos; with the common goal of distribution.

With the vast improvement of eSystems, integration of video processing, the transfer of live multimedia became possible and be used to access information in live sessions. This process has been used for video conferencing, live news, and social feeds. 

As for video streaming and distribution is used, little is known about the backhand of the process which involves in the technology. This paper looks into the backflow of video streaming.

### Video Compression
H.264 is the standard video coding system that combines block-wise transformation coding and predictive coding to reduce the redundancy of a video. The coding adopts a hierarchical block structure of code unit, a prediction unit and a transforms unit. The coding system divides the picture into slices of code unit tree which is then further divided to create the smallest possible code unit. The data is then processed into a prediction mode and partition size to be stored/transfer. The predictive unit when called upon, then merges the code units or further advancement to the image if requested. (Yang, Lee, Shim & Jeon, 2013)

### Video Streaming
Multimedia applications have experienced growth over the past decade with the change to High Definition, 4K resolution, SDTV, and, more. Although the accomplishment with media applications, video streaming services still face issues to guarantee high quality of service. Often the cost of bandwidth, delay, and perhaps unstable servers. The problem often directed towards wireless hops which include interference, shadowing, and mobility. Protocols are designed to react to situations of occurrences such as Error resilience, video coding, forward error correction, rate-distortion, and error concealment (Setton & Girod, 2010)

#### Error Resilience
In the H264 process, picture data is compressed and divided into semi smaller code units. Video streaming is the transfer of code units through transfer protocols; through this transfer, data may be lost due to decoding faulty or loss packets in the transfer. Error control techniques are called upon during the transmission error. While it is impossible to retrieve missing data, the technique uses low latencies to create stability 

#### Video Coding 
Due to low bandwidth and bitstream, an alternative solution is to create a lower coding efficiency. The result causes a lower compressed video and minimizes the distortion of videos that may occur. The principle operates under the picture selection algorithm. 

#### Forward Error Correction
Forward Error Correction is the method of controlling possible error with data transmission. The process requires the sender to send the packets twice and observes the instances and data from the packets. The protocol checks the different layers of bit-rate and combines the partition segments. 

#### Rate-Distortion
The Rate-Distortion analyzes video displacement similar to the forward error correction based approach, but focus on the individual packets that are missing. As data have timestamps and protocols, packets missing can be tracked. The missing packets are then requested back from the server end to obtain missing segments. This approach looks for the important packets missing rather than resending the whole set of packets.

#### Error Concealment
When the packets that are missing and cannot be avoided, time allocation is limited to prevent the stoppage. Error concealment is then called upon to create a visual artifact of the assumed image. The temporal interpolation algorithm artifacts of large displacements to estimate motion and image trajectories. 

## Video Compression Coding
The following represents a basic video processing coding standards 
#### Transformation Block
The first step of video image/coding is the division of an image into small blocks. The blocks of pixels are then converted into a frequency domain. This process is called the Discrete Cosine Transform. WDCT helps separate more perceptible information from less perceptible information. 
#### Quantization
As the frequency domain varies and is real numbers, quantization rounds the numbers to their closest integer. While high-frequency DCT that are close to zero will bet set to 0

#### Entropy Coding
Nonzero coefficients are encoded by an entropy coder. Zero coefficients are encoded with run-length encoding. The higher the frequency, the shorter code, and vice versa. 
#### Decoding
The variable-length code is decoded back to the quantized coefficient. The value is then multiplied by the appropriate quantizer step size to get the DCT coefficients. With the DCT coefficients, the value is put in the inverse DCT to get the value of the domain. 
#note: the image will not be identical to the original image due to loss of information in quantization
#### Motion Estimation and Compensation
The motion feature is used as the reference frame to predict the current frame. With the predicted new frame is close to the actual frame size, the coded data is less than the original. The process is repeated over each block and processed in a timestamp.

*Motion estimate is required more computation resource hence, requires the highest activity in the video process.*

## Conclusion
Multimedia operates cover multiple encryption compression of data to smaller bits. The bits are transfers and encrypted before sending through various network protocol and packets transfer. During the transfer protocols, information may be lost, altered, or stolen which causes visual delays. Delays often happen over the speed of the multimedia process with limited information. Although internet bandwidth and traffic often are the cause of delays, video processing and encryption may have effects on the video. 

## Reference
Chakrabarti, I., Batta, K., & Chatterjee, S. (2015). Motion Estimation for Video Coding. Cham: Springer International Publishing.Yang, 

S., Lee, H., Shim, H., & Jeon, B. (2013). Fast inter mode decision process for HEVC encoder. IVMSP 2013. doi: 10.1109/ivmspw.2013.6611927

Setton, E., & Girod, B. (2010). Peer-to-peer video streaming. New York: Springer.
