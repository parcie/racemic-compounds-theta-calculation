# racemaic-compounds-theta-calculation
## Authorship and Purpose

This repository is maintained by the authors of the associated study: Weihao Wang (王卫豪), Fangyi Chen (陈方夷), Zhenghong Chen (陈政宏), Yutong Sun (孙雨桐), and Shaodong Zhang (张绍东).

It provides the source code and datasets used to calculate the theta angle defined in our article on racemic compound crystals. The implementation is primarily designed for crystal structures with a Z′ value of 1.

The GitHub username is used solely for repository management and does not necessarily reflect the authors’ real names.

This project uses:
	•	Python 3.9.0
	•	numpy 1.26.4
	•	pandas 2.2.3
	•	gemmi 0.6.7
	•	ccdc 3.3.1
	•	openpyxl 3.1.5

The CSD Python API can be installed on all supported platforms via conda from the CCDC conda channel. The  detailed instructions can be found in the CCDC official tutorials at 
https://downloads.ccdc.ac.uk/documentation/API/ installation_notes
Or, refer to code in GitHub:
https://github.com/ccdc-opensource/csd-python-api-scripts.
The ccdc module need official license that given by CCDC

To recreate the environment:
conda env create -f environment.yml
conda activate csd
