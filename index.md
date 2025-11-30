---
layout: default
---

> ...the Cartographers Guilds made a Map of the Empire whose size was that of the Empire, and which coincided point for point with it.
>
> — J.L. Borges. _On Rigor in Science._ (1946)

# Learning AS-to-Organization Mappings with Borges

**Carlos Selmo**, **Esteban Carisimo**, **Fabián E. Bustamante**, **J. Ignacio Alvarez-Hamelin**

<div class="warning-box">
⚠️ <strong>Important Notice:</strong> The artifacts below were generated in September 2025. Internet infrastructure changes rapidly—during our research, companies like Edgio disappeared between submission and presentation. We strongly recommend regenerating the data using our tool (one-click run, ~$3 USD). Things go stale quickly in the Internet ecosystem.
</div>

## Abstract

Borges is a Python package and CLI tool that maps Autonomous Systems (ASNs) to their parent organizations, revealing the true corporate structure of the Internet. It is based on research published at the [ACM Internet Measurement Conference (IMC) 2025](https://conferences.sigcomm.org/imc/2025/). By combining traditional WHOIS data with AI-powered analysis of websites, favicons, and unstructured text, Borges uncovers hidden relationships that existing methods miss.

Our approach achieves 0.947 accuracy in extracting sibling AS relationships and outperforms prior systems by 7% on the Organization Factor metric. This improved mapping reveals approximately 192 million previously uncounted Internet users and enables better understanding of Internet resilience, incident response, and market concentration.

## Key Features

- **Multi-source AS Detection**: Combines PeeringDB, WHOIS, website analysis, and favicon similarity
- **AI-Powered Analysis**: Uses LLMs for text extraction and computer vision for favicon comparison
- **Lightweight & Repeatable**: Designed for regular inexpensive updates as Internet infrastructure evolves
- **High Accuracy**: 94.7% precision in identifying sibling AS relationships

## Downloads

- 📄 [Paper PDF](/assets/borges-paper.pdf) - Full paper as presented at ACM IMC 2025
- 📦 [Artifacts (Sept 2025)](/assets/borges-artifacts-sept25.zip) - Dataset and supplementary materials
- 💻 [GitHub Repository](https://github.com/NU-AquaLab/borges) - Source code and documentation

## Citation

```bibtex
@inproceedings{borges:imc,
    author = {Carlos Selmo and Esteban Carisimo and 
              Fabián E. Bustamante and J. Ignacio Alvarez-Hamelin},
    title = {Learning AS-to-Organization Mappings with Borges},
    booktitle = {Proc. of ACM IMC},
    year = {2025},
    month = {10}
}
```

## Press Coverage

### [Mapping Who Really Runs the Internet: Introducing Borges](https://pulse.internetsociety.org/blog/mapping-who-really-runs-the-internet-introducing-borges)
*Internet Society Pulse* - An in-depth look at how Borges reveals the hidden corporate structure of the Internet and its implications for policy and resilience.

### Social Media

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Excited to share our work on Borges at IMC 2025! We built a system that maps who really controls Internet infrastructure by combining AI/ML with traditional network analysis. Check out how we uncovered 192M hidden Internet users: <a href="https://github.com/NU-AquaLab/borges">github.com/NU-AquaLab/borges</a></p>&mdash; Esteban Carisimo (@estcarisimo) <a href="https://twitter.com/estcarisimo/status/1958054727242985660?ref_src=twsrc%5Etfw">November 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## About the Name

The project is named after Jorge Luis Borges, the renowned Argentine writer whose story "On Rigor in Science" describes cartographers creating a map so detailed it becomes as large as the territory itself. Like Borges's fictional map, our tool aims to create a comprehensive representation of Internet ownership—though thankfully, in a more manageable format.