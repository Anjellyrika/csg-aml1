We investigate the model SeqFakeFormer, with the corresponding dataset Seq-Deepfake, as presented in the paper:

**Title**: Detecting and Recovering Sequential DeepFake Manipulation <br>
**Authors**: Rui Shao, Tianxing Wu, and Ziwei Liu <br>
**Published in**: [ECCV 2022](https://eccv2022.ecva.net/) <br>
**Paper Link**: https://arxiv.org/pdf/2207.02204 <br>
**Original Repository**: [SeqDeepFake](https://github.com/rshaojimmy/SeqDeepFake/) <br>
**Dataset**: [Seq-DeepFake](https://huggingface.co/datasets/rshaojimmy/Seq-DeepFake) <br>

Please refer to the original paper for detailed information on the model architecture and dataset preparation.

## Modifications
For our use of the model, we used Python packages as specified in the [environment.yml](environment.yml) file.

## Initial Test Results
Testing the pre-trained models with the provided [testing script](https://github.com/rshaojimmy/SeqDeepFake/blob/master/test.sh) yielded results as shown in [pretrained-r50-c-evaluation.txt](pretrained-r50-c-evaluation.txt) for facial components and [pretrained-r50-a-evaluation.txt](pretrained-r50-a-evaluation.txt) for facial attributes. The pre-trained models were able to generate the accuracy scores as reported in the original Seq-DeepFake [benchmark results](https://github.com/rshaojimmy/SeqDeepFake?tab=readme-ov-file#benchmark-results): for facial components, 72.657\% fixed accuracy score and 55.304\% adaptive accuracy score, and for facial attributes, 68.856\% fixed accuracy score and 49.635\% adaptive accuracy score.

## License
The original Seq-DeepFake dataset is licensed under Apache 2.0, and can be found [here](https://huggingface.co/datasets/choosealicense/licenses/blob/main/markdown/apache-2.0.md).

## Citation
Citation for the original SeqDeepFake paper:

```bibtex
@inproceedings{shao2022seqdeepfake,
  title={Detecting and Recovering Sequential DeepFake Manipulation},
  author={Shao, Rui and Wu, Tianxing and Liu, Ziwei},
  booktitle={European Conference on Computer Vision (ECCV)},
  year={2022}
}
```
