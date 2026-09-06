# Bluevision AI Academy — Labs

Free, self-contained Colab notebooks that go with the [Bluevision AI](https://www.youtube.com/@BlueVision-AI) YouTube channel — hands-on companions to Dr Vahid Seydi's lectures on machine learning and AI, from [Bluevision AI Academy](https://bluevision-ai.org), the education arm of Bluevision AI.

Our goal is to help you become a creator of AI, not simply a user: every lecture's notebook lets you code the idea yourself.

Notebooks are pushed here as soon as each session is ready, independent of when the matching video is published. Open a notebook directly in Colab, no setup required.

## Structure

One folder per course, one subfolder per session:

```
<course>/<session-slug-or-number>/<session>_lab.ipynb
```

For example, a standalone single-topic session:

```
ml-foundations/retrieval/retrieval_lab.ipynb
```

and a numbered course session:

```
LLM/session01/session01_lab.ipynb
```

## Notebooks

| Course | Session | Video | Notebook |
|---|---|---|---|
| ml-foundations | Retrieval: Finding Similar Items Without Labels | Rebuilding — video coming soon | [Open notebook](ml-foundations/retrieval/retrieval_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/ml-foundations/retrieval/retrieval_lab.ipynb) |
| ml-foundations | k-Means: Finding Groups Without Labels | Rebuilding — video coming soon | [Open notebook](ml-foundations/k-means/k-means_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/ml-foundations/k-means/k-means_lab.ipynb) |
| ml-foundations | Gaussian Mixture Models: Soft Clustering with EM | Rebuilding — video coming soon | [Open notebook](ml-foundations/gaussian-mixtures/gaussian-mixtures_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/ml-foundations/gaussian-mixtures/gaussian-mixtures_lab.ipynb) |
| LLM | Session 01 — Why Language Is Hard | [Watch](https://www.youtube.com/watch?v=reWtLSQwy0w) | [Open notebook](LLM/session01/session01_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/LLM/session01/session01_lab.ipynb) |
| LLM | Session 04 — The Attention Breakthrough | [Watch](https://youtu.be/YKDHcsMEADw) | [Open notebook](LLM/session04/session04_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/LLM/session04/session04_lab.ipynb) |
| LLM | Session 05 — The Transformer Architecture | [Watch](https://youtu.be/-FhUEaRb_Ik) | [Open notebook](LLM/session05/session05_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/LLM/session05/session05_lab.ipynb) |
| LLM | Session 06 — BERT: Reading the Whole Sentence | [Watch](https://youtu.be/IAjdK89WVYc) | [Open notebook](LLM/session06/session06_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/LLM/session06/session06_lab.ipynb) |
| LLM | Session 07 — GPT: Predicting What Comes Next | Coming soon | [Open notebook](LLM/session07/session07_lab.ipynb) · [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bluevision-ai/academy-labs/blob/main/LLM/session07/session07_lab.ipynb) |

## Licence

Two things live side by side here, under two licences:

- **The notebooks in this repository — MIT** (see [`LICENSE`](LICENSE)). Reuse, adapt and remix
  freely; attribution appreciated but not required.
- **The lectures they accompany — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).**
  Slides, figures, diagrams, narration and video may be reused and adapted, including commercially,
  **provided you give credit**. Copying a figure out of a lecture is not covered by the MIT licence
  above.

## Citing this work

Cite the **lecture**, not the notebook, unless you are specifically citing the code:

> Seydi, V. (2026). *Session NN: Title* [Video lecture]. *Course Name*. Bluevision AI. URL

```bibtex
@misc{seydi2026,
  author       = {Seydi, Vahid},
  title        = {Session NN: Title},
  howpublished = {Video lecture, \emph{Course Name}},
  organization = {Bluevision AI},
  year         = {2026},
  url          = {https://www.youtube.com/@BlueVision-AI}
}
```

GitHub's "Cite this repository" button (from [`CITATION.cff`](CITATION.cff)) gives the notebook
citation in APA and BibTeX. Per-session DOIs are planned; once a session has one, prefer the DOI
over the video URL.
