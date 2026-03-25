<!-- PROJECT LOGO -->
<br />
<div align="center">

<h2 align="center">IndoBERT Model for Online Gambling Ads Detection</h2>

  <p align="center">
    This model is a fine-tuned version of IndoBERT (p2 variant) specifically designed to detect online gambling advertisements.
    <br />
    <a href="https://huggingface.co/walkervs/indobert-detect-judol"><strong>HuggingFace Link</strong></a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

The phenomenon of online gambling exploitation on donation platforms like Saweria or Trakteer has become a significant headache for content creators. Exploiting low minimum donation thresholds, gambling agents use these "overlay alerts" as cheap billboard space to broadcast intrusive ads directly to thousands of live viewers. While these platforms offer basic word-blocking features, they often fail against creative "leetspeak" or symbolic variations, forcing streamers to manually ban words mid-broadcast. This project introduces a Pre-processing Filtration System powered by a fine-tuned IndoBERT model, designed to act as an intelligent gatekeeper that validates and blocks gambling content at the API level before it ever reaches the streamer's screen.

### Built With

[![Built With](https://skillicons.dev/icons?i=python,scikitlearn,pytorch&theme=light)](https://skillicons.dev)

<!-- GETTING STARTED -->
## Getting Started

I use uv instead of pip/miniconda as dependency manager. See the documentation here: https://docs.astral.sh/uv/

### Prerequisites

If you run this in visual studio code, use this command to create the kernel:

`uv run python -m ipykernel install --user --name=nojudol --display-name "Python (your-kernel-name)"`

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- CONTACT -->
## Contact

Walker - walkervalentinussimanjuntak@gmail.com