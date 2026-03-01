# @GROKSET: Human-LLM Interactions in Social Media

This repository contains the project page for the @GROKSET research paper, which presents the first large-scale dataset of multi-party human-LLM interactions in public social media.

## Project Overview

Large Language Models (LLMs) are increasingly deployed as active participants on public social media platforms, yet their behavior in these unconstrained social environments remains largely unstudied. @GROKSET addresses this gap with a dataset of over 1 million tweets involving the GROK LLM on X (formerly Twitter).

### Key Findings

1. **The Arbiter in the Loop**: Users frequently invoke the LLM not as a social peer, but as an authoritative arbiter in high-stakes, polarizing debates regarding elections, conflicts, and social controversies.

2. **The Engagement Gap**: Despite deployment in contentious public spaces, the model is treated as a low-engagement utility. Human-authored content receives significantly more social validation (likes, replies) than LLM outputs.

3. **Shallow Alignment**: The adversarial nature of public discourse exposes brittle safety mechanisms. Users bypass safety filters not through complex technical attacks, but through simple persona adoption and tone mirroring.

## Dataset Statistics

- **Total Tweets**: 1,098,394
- **Conversations**: 182,707
- **Unique Users**: 241,386
- **Average Turns per Conversation**: 6.01
- **Collection Period**: 7 months (March - October 2025)
- **Key Feature**: Multi-party dynamics with rich engagement metadata

## Features

Unlike existing datasets from private chat interfaces (WildChat, LMSYS-Chat-1M, StudyChat), @GROKSET captures:
- Multi-party conversations with complex social dynamics
- Public discourse in adversarial, performative contexts
- Rich engagement metadata (likes, retweets, replies, bookmarks)
- Real-world high-stakes political and social debates

## Project Page

The project page is hosted at: [https://sarahlz01.github.io/GrokResearch](https://sarahlz01.github.io/GrokResearch)

To view the page locally, simply open `index.html` in a web browser.

## Repository Structure

```
.
├── index.html              # Main project page
├── static/
│   ├── css/               # Stylesheets (Bulma framework)
│   ├── js/                # JavaScript files
│   ├── pdfs/              # Paper PDF
│   └── images/            # Figures and visualizations
│       ├── Dataset/       # Dataset statistics figures
│       └── Topic_analysis/# Topic modeling visualizations
└── README.md              # This file
```

## Citation

If you use this dataset in your research, please cite:

```bibtex
@misc{migliarini2026grokset,
      title={@GrokSet: multi-party Human-LLM Interactions in Social Media}, 
      author={Matteo Migliarini and Berat Ercevik and Oluwagbemike Olowe and Saira Fatima and Sarah Zhao and Minh Anh Le and Vasu Sharma and Ashwinee Panda},
      year={2026},
      eprint={2602.21236},
      archivePrefix={arXiv},
      primaryClass={cs.SI},
      url={https://arxiv.org/abs/2602.21236}, 
}
```

## Authors

- Matteo Migliarini* (Sapienza University)
- Berat Ercevik* (University of California Santa Cruz)
- Oluwagbemike Olowe (University of Calgary)
- Saira Fatima (University of Calgary)
- Sarah Zhao (University of Calgary)
- Minh Anh Le (University of Utah)
- Vasu Sharma (Meta FAIR)
- Ashwinee Panda (University of Maryland)

*Equal contribution

## Acknowledgements

This research was funded by **Algoverse AI Research**. We gratefully acknowledge their support in making this work possible.

## Warning

This paper contains data and model outputs which are offensive in nature, as it analyzes real-world interactions in public social media environments.

## Website Template

This project page was built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) which was adopted from the [Nerfies](https://nerfies.github.io) project page.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
