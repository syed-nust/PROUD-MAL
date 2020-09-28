# PROUD-MAL
Enterprises are striving to remain protected against the malware based cyber-attacks over their infrastructure, facilities, networks and systems. Static analysis is an effective approach to detect the malware i.e. malicious Portable Executable(PE). It performs the in depth analysis of PE files without executing them, which is highly effective to minimize the risk of malicious PE contaminating the system and allowing its early stage detection.Yet, the instant detection using static analysis has become very difficult due to the exponential rise in volume and variety of malware. The compelling need of early stage detection of malware based attacks significantly motivates research inclination towards automated malware detection and classification. The recent machine learning aided malware detection approaches using static analysis are mostly supervised. Supervised malware detection using static analysis is based on manual labelling and human feedback and therefore less effective in rapidly evolutionary and dynamic threat space.To this end, we propose a Progressive Unsupervised Deep architecture PROUD-MAL.The DeepMAL employed the attention-based feature processing that resulted in the refined contextual information by keeping the attention on the object of interest significant for malware detection. The feature attention based layer learns to put relatively more weights to those features that contributed more to minimize the validation loss while learning the accurate classification. It provides a proactive approach significantly swift and less resource intensive as compare to dynamic analysis.To evaluate the proposed unsupervised framework, we collected a real-time malware dataset by deploying low and high interaction honey pots on an enterprise organizational network. Moreover, endpoint security solution is also deployed over the enterprise organizational network to collect malware samples. After postprocessing and cleaning, the dataset is comprised of 15457 Pes, out of which 8775 are malicious and 6681 are benign samples.The proposed DeepMAL framework achieved better quantitative performance in standard evaluation metrices on this dataset and outperformed other classical machine learning algorithms.
# Data Description
Different scheme was used for collecting the malicious and benign samples. In order to collect malicious files, low interaction honey pots to emulate the services frequently targeted by the attacker and high interaction honey pots to emulates the production systems were deployed. Moreover, endpoint security solution is also deployed over the enterprise organizational network to collect malware samples. The benign PE including .exe or .dll are collected from machines with licensed and updated version of Windows operating system including Windows XP, 7, 8 and 10. Special precautions have been taken into account for compliance of licensing and regulatory requirements while collecting benign samples. The collected samples were approximately 19000 but after performing EDA, samples were reduced to 15457 comprising malicious and benign samples i.e. 8775 and 6681 respectively. The reduction in number of samples resulted due to filtering of corrupt and duplicate samples. The validation of samples and removal of duplicate samples was done using the virus total web api.

## DataSet Link
* [Dataset](https://vision.seecs.edu.pk)
* [Labels](https://docs.google.com/forms/d/e/1FAIpQLSfynrGmjI7kDSoot6GsGDSbktLDPNtMWK5PjZ9WV5f5UO2B9A/viewform?usp=sf_link)


