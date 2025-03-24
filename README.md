# AudioLM-position-paper
This repo contains the code and audio samples for the position paper ["The Deployment of End-to-End Audio Language Models Should Take into Account the Principle of Least Privilege"](https://arxiv.org/abs/2503.16833).  

**Abstract:** We are at a turning point for language models that accept audio input. The latest end-to-end audio language models (Audio LMs) process speech directly instead of relying on a separate transcription step. This shift preserves detailed information, such as intonation or the presence of multiple speakers, that would otherwise be lost in transcription. However, it also introduces new safety risks, including the potential misuse of speaker identity cues and other sensitive vocal attributes, which could have legal implications. In this position paper, we urge a closer examination of how these models are built and deployed. We argue that the principle of least privilege should guide decisions on whether to deploy cascaded or end-to-end models. Specifically, evaluations should assess (1) whether end-to-end modeling is necessary for a given application; and (2), the appropriate scope of information access. Finally, We highlight related gaps in current audio LM benchmarks and identify key open research questions, both technical and policy-related, that must be addressed to enable the responsible deployment of end-to-end Audio LMs.

## Audio samples
Please visit this [link](https://drive.google.com/drive/folders/1G9bSxV2haucayqJuYrWQ8q5YG8JaPlgI?usp=sharing) to access the shortlist of 30 audio clips for each of the 12 individuals we study in Section 2. The clips were collected from YouTube videos released **after** June 2024, and the transcripts of these audios are included in ```Transcripts_All.xlsx```. For all of the audios, GPT-4o has correctly inferred the person’s identity from the voices. 

## Citation
```
@misc{he2025deploymentendtoendaudiolanguage,
      title={The Deployment of End-to-End Audio Language Models Should Take into Account the Principle of Least Privilege}, 
      author={Luxi He and Xiangyu Qi and Michel Liao and Inyoung Cheong and Prateek Mittal and Danqi Chen and Peter Henderson},
      year={2025},
      eprint={2503.16833},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2503.16833}, 
}
```
