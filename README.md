# Individual Packet Features are a Risk to Model Generalisation in ML-Based Intrusion Detection.

# Overview
In this repository you will find a Python implementation of the methods in the paper [Individual Packet Features are a Risk to Model Generalisation in ML-Based Intrusion Detectionn](https://arxiv.org/abs/2406.07578)


# Abstract

Machine learning is increasingly used for intrusion detection in IoT networks. This paper explores the effectiveness of using individual packet features (IPF), which are attributes extracted from a single network packet, such as timing, size, and source-destination information. Through literature review and experiments, we identify the limitations of IPF, showing they can produce misleadingly high detection rates. Our findings emphasize the need for approaches that consider packet interactions for robust intrusion detection. Additionally, we demonstrate that models based on IPF often fail to generalize across datasets, compromising their reliability in diverse IoT environments.



# Requirements and Infrastructure: 

Wireshark and Python 3.10 were used to create the application files. Before running the files, it must be ensured that [Wireshark](https://www.wireshark.org/), [Python 3.6+](https://www.python.org/downloads/) and the following libraries are installed.

| Library | Task |
| ------ | ------ |
|[ Sklearn ](http://scikit-learn.org/stable/install.html)| Machine Learning & Data Preparation |
| [ Numpy ](http://www.numpy.org/) |Mathematical Operations|
| [ Pandas  ](https://pandas.pydata.org/pandas-docs/stable/install.html)|  Data Analysis|
| [ Matplotlib ](https://matplotlib.org/users/installing.html) |Graphics and Visuality|
| [Seaborn ](https://seaborn.pydata.org/) |Graphics and Visuality|


# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


# Citations
If you use the source code please cite the following paper:

*Kahraman  Kostas,  Mike  Just,  and  Michael  A.  Lones.   Individual Packet Features are a Risk to Model Generalisation in ML-Based Intrusion Detection., arXiv preprint, arxiv:2406.07578, 2024*


```
@misc{kostas2023IoTGeM,
      title={Individual Packet Features are a Risk to Model Generalisation in ML-Based Intrusion Detection.}, 
      author={Kahraman Kostas and Mike Just and Michael A. Lones},
      year={2024},
      eprint={2406.07578},
      archivePrefix={arXiv},
      primaryClass={cs.CR}



}
```

Contact:
*Kahraman Kostas
kahramankostas@gmail.com*
