---
layout: home
---

🎉 I first became interested in artificial neural networks (ANN) when I first read a blog by Richard Nagyfi titled as [The differences between Artificial and Biological Neural Networks][ANN]. ANNs are inspired by how millions of neurons in the human brain make decisions. Though there are many differences between artificial and biological neural networks, extensive research to train machines to think like a human brain has always fascinated me. I am currently working on sound event detection with the help of source separation. I will try to provide updates here.

[ANN]: https://towardsdatascience.com/the-differences-between-artificial-and-biological-neural-networks-a8b46db828b7

I'm a a post-graduate (M.Sc.) student from the department of [Electrical and Electronic Engineering][EEE] at [Bangladesh University of Engineering and Technology (BUET)][BUET]. I have also been working as a Research Assistant in the same department, supervised by Prof. Dr. Mohammad Ariful Haque. My primary research interests include **applied deep learning & investigation of neural networks**. Apart from that, I have research experience on optimised load management of Smart Grids (SG).

[EEE]: http://www.eee.buet.ac.bd/
[BUET]: https://www.buet.ac.bd/
[hci]:http://hci.stanford.edu/
[hancock]: https://comm.stanford.edu/faculty-hancock/
[penncis]: https://www.cis.upenn.edu
[pennasc]: https://www.asc.upenn.edu
[pacs]: https://pacscenter.stanford.edu
[pdi]: https://pacscenter.stanford.edu/research/program-on-democracy-and-the-internet/
[amh]: http://andrewhead.info

Projects I've worked on include [identifying ALS from raw EMG signal][als], [search and rescue with drone-embedded sound source localization][sound-source-localization], [direction of arrival estimation through noise suppression][doa-estimation], and [dual-purpose refreshable braille display based on real time object detection and optical character recognition][braille], [electrical power consumption profile modelling of air conditioner for Smart Grid load management][profile-modelling-sg].

[als]: https://doi.org/10.1109/ICASSP43922.2022.9747366
[sound-source-localization]: https://doi.org/10.1186/s13636-020-00184-2
[doa-estimation]: https://doi.org/10.1109/SPICSCON48833.2019.9065151
[braille]: https://doi.org/10.1109/SPICSCON48833.2019.9065110
[profile-modelling-sg]: https://doi.org/10.1109/ICECE51571.2020.9393101

I graduated with B.Sc. degree in Electrical and [Electrical and Electronic Engineering][EEE] at [Bangladesh University of Engineering and Technology (BUET)][BUET] in 2021. 

P.S. My nickname is "Prangon". 

---

## Research Highlights 



### [ALSNet: A Dilated 1-D CNN for Identifying ALS from Raw EMG Signal][alsnet]


<center style="padding: 10px;">
<img src="media/als.jpg"
     style="max-width: 85%;" />
</center>

**K. M. Naimul Hassan**, Md. Shamiul Alam Hridoy, Naima Tasnim, Atia Faria Chowdhury, Tanvir Alam Roni, Sheikh Tabrez, Arik Subhana, Celia Shahnaz _(Published on April 27, 2022 in 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP))_

Amyotrophic Lateral Sclerosis (ALS) is one of the most common neuromuscular diseases which affects both lower and upper motor neurons. In this paper, a dilated one dimensional convolutional neural network, named ALSNet, is proposed for identifying ALS from raw EMG signal. No hand-crafted feature extraction is required, rather, ALSNet is able to take raw EMG signal as input and detect EMG signals of ALS subjects. This makes the method more feasible for practical implementation by reducing the computational cost required for extracting features. To our best knowledge, no research work for identification of ALS from raw EMG signal has been conducted yet. The performance of the ALSNet was evaluated using popular metrics such as overall accuracy, sensitivity, specificity and balanced accuracy and compared with other existing methods. The proposed method showed a better performance than the other existing methods with an overall accuracy of 97.74%.

[alsnet]: http://naimulhassan.github.io/content/papers/alsnet.pdf 


### [DOANet: a deep dilated convolutional neural network approach for search and rescue with drone-embedded sound source localization][doanet-ssl]


<center style="padding: 10px;">
<img src="media/ssl.png"
     style="max-width: 85%;" />
</center>

Alif Bin Abdul Qayyum, **K M Naimul Hassan**, Adrita Anika, Md. Farhan Shadiq, Md. Mushfiqur Rahman, Md. Tariqul Islam, Sheikh Asif Imran, Shahruk Hossain & Mohammad Ariful Haque _(Published on November 5, 2020 in EURASIP Journal on Audio, Speech and Music Processing)_

Drone-embedded sound source localization (SSL) has interesting application perspective in challenging search and rescue scenarios due to bad lighting conditions or occlusions. However, the problem gets complicated by severe drone ego-noise that may result in negative signal-to-noise ratios in the recorded microphone signals. In this paper, we present our work on drone-embedded SSL using recordings from an 8-channel cube-shaped microphone array embedded in an unmanned aerial vehicle (UAV). We use angular spectrum-based TDOA (time difference of arrival) estimation methods such as generalized cross-correlation phase-transform (GCC-PHAT), minimum-variance-distortion-less-response (MVDR) as baseline, which are state-of-the-art techniques for SSL. Though we improve the baseline method by reducing ego-noise using speed correlated harmonics cancellation (SCHC) technique, our main focus is to utilize deep learning techniques to solve this challenging problem. Here, we propose an end-to-end deep learning model, called DOANet, for SSL. DOANet is based on a one-dimensional dilated convolutional neural network that computes the azimuth and elevation angles of the target sound source from the raw audio signal. The advantage of using DOANet is that it does not require any hand-crafted audio features or ego-noise reduction for DOA estimation. We then evaluate the SSL performance using the proposed and baseline methods and find that the DOANet shows promising results compared to both the angular spectrum methods with and without SCHC. To evaluate the different methods, we also introduce a well-known parameter—area under the curve (AUC) of cumulative histogram plots of angular deviations—as a performance indicator which, to our knowledge, has not been used as a performance indicator for this sort of problem before.

[doanet-ssl]: http://naimulhassan.github.io/content/papers/doanet-ssl.pdf



### [Electrical Power Consumption Profile Modelling of of Air Conditioner for Smart Grid Load Management][profile-modelling]


<center style="padding: 10px;">
<img src="media/sg.png"
     style="max-width: 85%;" />
</center>

**K M Naimul Hassan**, Soumav Biswas & Md. Forkan Uddin _(Published in 2020 11th International Conference on Electrical and Computer Engineering (ICECE))_

Air conditioning (AC) system will be an inherent part of smart grid (SG) demand response as it is responsible for a substantial amount of power consumption in total infrastructure. It is invaluable to estimate the nature of operational characteristics of AC compressors in order to implement associated optimization strategy for energy preservation in residential premises. In this paper, the electrical power consumption profile, i.e., On-time and Off-time durations and power consumptions during these time durations is modelled for a split type AC compressor in terms of co-efficient of performance, AC capacity and environment condition. Dead-band temperature and room dimensions are considered as environment condition and the effect of various parameters on On-time and Off-time durations and energy consumption is studied. The factors that can be optimized to reduce the energy consumption are also analyzed.

[profile-modelling]: http://naimulhassan.github.io/content/papers/profile-modelling-sg.pdf



---

## Other Recent Publications
For a complete list of my academic publications, see my [Google Scholar page][scholar].

[scholar]: https://scholar.google.com/citations?user=ondPg7wAAAAJ&hl=en&oi=sra



---
## Notable Achievements

I have participated in multiple student competitions during my undergraduate.

### [IEEE Video and Image Processing (VIP) Cup 2019: Privacy-aware office activity recognition from First Person View (FPV) body cameras][vip2019]


<center style="padding: 10px;">
<img src="media/vip2019.png"
     style="max-width: 85%;" />
</center>

Team: BUET Ravenclaw

Undergraduate Team Members: [from left] Sheikh Asif Imran Shouborno, Md. Mushfiqur Rahman, Md. Tariqul Islam & **K M Naimul Hassan**

Supervisor: Dr. Mohammad Ariful Haque

Final at 26th IEEE Conference on Image Processing (ICIP) 2019, Taipei, Taiwan

[vip2019]: http://naimulhassan.github.io/content/papers/vip2019.pdf

### [IEEE Signal Processing (SP) Cup 2020: Unsupervised abnormality detection by using intelligent and heterogenous autonomous system][sp2020]


<center style="padding: 10px;">
<img src="media/sp2020.png"
     style="max-width: 85%;" />
</center>

Team: BUET Andromeda

Undergraduate Team Members: Shafin Bin Hamid, Munshi Sanowar Raihan, Ashiqur Rasul, Himaddri Roy, Prasun Datta, Mushfiqur Rahman & **K M Naimul Hassan**

Supervisor: Dr. Mohammad Ariful Haque

Final at 45th IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2020, Barcelona, Spain. [Organized as a Virtual Conference]

[sp2020]: http://naimulhassan.github.io/content/papers/sp2020.pdf




---
## Other Achievements
For a complete list of honor/achievements, see my [Academic CV][academic-cv].

[academic-cv]: http://naimulhassan.github.io/content/papers/naimulCV.pdf	
