# How Deep Is Representational Bias in LLMs? The Cases of Caste and Religion

This repository contains the data and code for our paper examining representational bias in GPT-4 Turbo with respect to caste and religion in India.

## Overview

We analyze 7,200 GPT-4 Turbo generated stories about life rituals (birth, wedding, death) across four Indian states to quantify the extent of representational bias. Our findings reveal:

- **Severe underrepresentation**: General castes are overrepresented by 34-57 percentage points above their actual population
- **Deep entrenchment**: Diversity prompts provide only inconsistent and partial bias mitigation
- **Winner-takes-all dynamics**: Even marginal statistical advantages lead to near-total dominance in outputs
- **Systematic erasure**: 64% of India's population (SC/ST/OBC groups) are dramatically underrepresented

## Paper

**Published in:** Proceedings of the Eighth AAAI/ACM Conference on AI, Ethics, and Society (AIES 2025)

📄 [Read the paper](https://ojs.aaai.org/index.php/AIES/article/view/36718) 

[Extended version] (https://arxiv.org/abs/2508.03712)


## Citation

If you use this dataset or code in your research, please cite:
```bibtex
@inproceedings{seth2025deep,
  title={How Deep Is Representational Bias in LLMs? The Cases of Caste and Religion},
  author={Seth, Agrima and Choudhury, Monojit and Sitaram, Sunayana and Toyama, Kentaro and Vashistha, Aditya and Bali, Kalika},
  booktitle={Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society},
  volume={8},
  number={3},
  pages={2319--2330},
  year={2025}
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

We encourage the use of this data to improve AI systems and advance fairness research. If you use this work to mitigate bias in commercial systems, we'd appreciate hearing about it (though this is not required by the license).

## Contact

For questions or collaboration opportunities, please contact:
- Agrima Seth: agrima@umich.edu

---

**Note:** This research examines bias in AI systems. The data contains examples of biased outputs for research purposes.
