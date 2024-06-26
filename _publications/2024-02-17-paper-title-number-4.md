---
title: "TiVHDR: Time-Aware SDR-HDR Video Translation"
collection: publications
permalink: /publication/paper4
excerpt: 'T. Qin, Z. He, Z. Ni, W. Yang, H. Wang, and S. Kwong'
date: 2024-6-20
venue: 'IEEE Transactions On Image Processing Under Review'
paperurl: #'http://academicpages.github.io/files/paper3.pdf'
citation: #'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---
High Dynamic Range (HDR) is a technology that enhances the visual experience of media by allowing visual content to display a wider range of brightness and colors. However, many existing videos are still limited to Standard Dynamic Range (SDR), which may result in inaccurate visual representation and impact the audience's viewing experience.Existing methods have made some progress in the transition from SDR pictures to HDR pictures. However, the transition from SDR videos to HDR videos does not receive enough attention. To address this issue, this paper explores a novel Time-Aware SDR to HDR Video Translation method, namely TiVHDR, aiming to consider the inter-frame relationships and transform SDR videos into HDR format. We first incorporate cutting-edge self-supervised pre-training strategies, i.e., Masked Image Modeling (MIM), with innovative approaches. Additionally, we propose using a recurrent neural network as the backbone, introducing the idea of dense connections to create a Dense Recurrent Network (DRN). Furthermore, recognizing that the current frame can learn complementary information from frames at the same scene, we design a Dynamic Memory Module (DMM) to introduce global information, allowing the input video frames to leverage information from any position in the video. Benefiting from these modules, our method is capable of produce accurate and robust videos. Lastly, after reviewing existing literature and conducting investigations, we found a lack of open-source video test sets for this task. Therefore, we created a new video test set. Extensive experiments demonstrate that our method effectively enhances the visual quality of SDR videos and competes favorably with state-of-the-art methods. 
