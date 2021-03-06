# IQM
IQM is a switch-based incast-aware congestion control scheme targeted for Data Centre Networks. Specifically, it aims at detecting incast in timely manner and sending explicit feedback information by rewritting the receiver window field of the backward ACKS. 

It is implemented as a load-able Linux-Kernel Module and as a Patch applicable to OpenvSwitch datapath

# Installation Guide
Please Refer to the \[[InstallME](InstallME.md)\] file for more information about installation and possible usage scenarios.

#Feedback
I always welcome and love to have feedback on the program or any possible improvements, please do not hesitate to contact me by commenting on the code [Here](https://ahmedcs.github.io/IQM-post/) or dropping me an email at [ahmedcs982@gmail.com](mailto:ahmedcs982@gmail.com). **PS: this is one of the reasons for me to share the software.**  

**This software will be constantly updated as soon as bugs, fixes and/or optimization tricks have been identified.**


# License
This software including (source code, scripts, .., etc) within this repository and its subfolders are licensed under CRAPL license.

**Please refer to the LICENSE file \[[CRAPL LICENCE](LICENSE)\] for more information**


# CopyRight Notice
The Copyright of this repository and its subfolders are held exclusively by "Ahmed Mohamed Abdelmoniem Sayed", for any inquiries contact me at ([ahmedcs982@gmail.com](mailto:ahmedcs982@gmail.com)).

Any USE or Modification to the (source code, scripts, .., etc) included in this repository has to cite the following PAPERS:  

1- Ahmed M. Abdelmoniem and Brahim Bensaou, “Incast-Aware Switch-Assisted TCP Congestion Control for Data Centers". In Proceedings of IEEE Global Communications Conference (IEEE GlobeCom), San Diego, USA, Dec 2015.  

**Notice, the COPYRIGHT and/or Author Information notice at the header of the (source, header and script) files can not be removed or modified.**


# Published Paper
To understand the framework and proposed solution, please read the paper "Incast-Aware Switch-Assisted TCP Congestion Control for Data Centers" \[[IQM Paper PDF](download/IQM.pdf)\]
