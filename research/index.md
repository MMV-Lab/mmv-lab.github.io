---
title: Research
nav:
  order: 1
  tooltip: research landscape
---

# <i class="fas fa-microscope"></i>Research

<p class="rs-lead">We build AI that answers real biomedical questions: efficient enough to run anywhere, trained on data worth trusting, and increasingly able to run the analysis itself.</p>

<div class="rs-grid">
  <a class="rs-tile" href="#application-driven">
    <span class="rs-num">01</span>
    <span class="rs-tile-title"><i class="fa-solid fa-flask"></i> Application-driven analysis</span>
    <span class="rs-tile-hook">Biology first, algorithm second.</span>
  </a>
  <a class="rs-tile" href="#efficient-ai">
    <span class="rs-num">02</span>
    <span class="rs-tile-title"><i class="fa-solid fa-bolt"></i> Efficient AI</span>
    <span class="rs-tile-hook">Lighter models, smaller data, better science.</span>
  </a>
  <a class="rs-tile" href="#ai-ready-data">
    <span class="rs-num">03</span>
    <span class="rs-tile-title"><i class="fa-solid fa-database"></i> AI-ready data</span>
    <span class="rs-tile-hook">Better AI starts with better data.</span>
  </a>
  <a class="rs-tile" href="#agents">
    <span class="rs-num">04</span>
    <span class="rs-tile-title"><i class="fa-solid fa-robot"></i> Agents &amp; foundation models</span>
    <span class="rs-tile-hook">Bioimage analysis, five years from now.</span>
  </a>
  <a class="rs-tile" href="#foundations">
    <span class="rs-num">05</span>
    <span class="rs-tile-title"><i class="fa-solid fa-compass"></i> Foundations &amp; frontiers</span>
    <span class="rs-tile-hook">The hard questions under every analysis.</span>
  </a>
  <a class="rs-tile" href="#outlook" data-outlook>
    <span class="rs-num">OUTLOOK</span>
    <span class="rs-tile-title"><i class="fa-solid fa-atom"></i> Multimodal AI</span>
    <span class="rs-tile-hook">Where and when, plus what.</span>
  </a>
</div>

<div class="rs-theme" id="application-driven">
  <h2><span class="rs-num">01</span> Application-driven bioimage analysis</h2>
  <p class="rs-hook">We start from the biological question, not the algorithm.</p>
  <p>We work side by side with immunologists, neuroscientists, and cardiovascular and cell biologists. When off-the-shelf software can't answer their question, we build the analysis that can: tracking thousands of migrating immune cells, mapping whole-organ vasculature, quantifying tissue change after stroke, building an integrated stem-cell model. Every analysis is validated against what the biology demands, which makes these partnerships our methods' hardest and most honest test.</p>
  <p class="rs-label">Selected work</p>
  <p class="rs-pills">
    <a href="https://www.nature.com/articles/s41586-022-05563-7">Integrated hiPS cell model <em>· Nature '23</em></a>
    <a href="https://www.nature.com/articles/s44161-024-00462-8">NETs after stroke &amp; MI <em>· Nat Cardiovasc Res '24</em></a>
    <a href="https://www.ahajournals.org/doi/10.1161/ATVBAHA.123.320339">Brain microvasculature after stroke <em>· ATVB '24</em></a>
    <a href="https://www.nature.com/articles/s41467-023-43765-3">ComplexEye <em>· Nat Commun '23</em></a>
    <a href="https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1014472">Uncertainty-aware cell migration <em>· PLOS Comput Biol '26</em></a>
    <a href="https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.76236">CD177 neutrophil subtype <em>· Adv Sci '26</em></a>
    <a href="https://link.springer.com/article/10.1186/s12974-025-03356-z">Shiga toxin neuroinflammation <em>· J Neuroinflamm '25</em></a>
    <a href="https://academic.oup.com/jleukbio/article-abstract/117/2/qiae250/8015881">Neutrophil migration <em>· J Leukoc Biol '25</em></a>
    <a href="https://doi.org/10.1016/j.cels.2025.101265">Nuclear growth trajectories <em>· Cell Syst '25</em></a>
  </p>
</div>

<div class="rs-theme" id="efficient-ai">
  <h2><span class="rs-num">02</span> Efficient AI for bioimaging</h2>
  <p class="rs-hook">High-end AI with lighter models and smaller data, for better science.</p>
  <p>Bioimaging AI only matters if labs can afford to run it and store what it produces. We make networks faster and less energy-hungry without losing accuracy. We also rethink how microscopy images are stored: learned compression, neural representations that encode an image as a compact function, and storage spent only where the biology is. The goal is terabyte-scale imaging that stays analyzable, shareable, and sustainable.</p>
  <p class="rs-label">Selected work</p>
  <p class="rs-pills">
    <a href="https://www.nature.com/articles/s41592-024-02167-z">EfficientBioAI <em>· Nat Methods '24</em></a>
    <a href="https://www.nature.com/articles/s42256-023-00670-0">Resource-aware AI <em>· Nat Mach Intell '23</em></a>
    <a href="https://www.nature.com/articles/s43588-025-00889-4">Implicit neural image fields <em>· Nat Comput Sci '25</em></a>
    <a href="https://openaccess.thecvf.com/content/CVPR2026/html/Pan_SGI_Structured_2D_Gaussians_for_Efficient_and_Compact_Large_Image_CVPR_2026_paper.html">SGI: 2D Gaussians <em>· CVPR '26</em></a>
    <a href="https://www.nature.com/articles/s44303-026-00178-3">FlowRoI <em>· npj Imaging '26</em></a>
    <a href="https://www.cambridge.org/core/journals/biological-imaging/article/deeplearningbased-image-compression-for-microscopy-images-an-empirical-study/7C9BF9F906A280BF3810EFEED512F913">Learned compression study <em>· Biol Imaging '24</em></a>
  </p>
</div>

<div class="rs-theme" id="ai-ready-data">
  <h2><span class="rs-num">03</span> AI-ready datasets</h2>
  <p class="rs-hook">Better AI needs better and more data, which requires modern data management.</p>
  <p>Most bioimage data never becomes useful for AI. It exists, but it is hard to find, poorly documented, or never quality-checked. We release datasets and benchmarks designed for machine learning from day one, and build the tools to organize, curate, and quality-control images at scale. For us, data release and data management go hand in hand: AI-readiness starts long before publication.</p>
  <p class="rs-label">Tools &amp; benchmarks</p>
  <p class="rs-pills">
    <a href="https://www.nature.com/articles/s41592-026-03130-w">BioFile Finder <em>· Nat Methods '26</em></a>
    <a href="https://www.nature.com/articles/s44303-025-00117-8">AutoQC-Bench <em>· npj Imaging '25</em></a>
    <a href="https://arxiv.org/abs/2609.34274">BIABench <em>· arXiv '26</em></a>
  </p>
  <p class="rs-label">Released datasets</p>
  <p class="rs-pills">
    <a href="https://www.nature.com/articles/s41586-022-05563-7">hiPS cell image atlas <em>· Nature '23</em></a>
    <a href="https://doi.org/10.1016/j.crmeth.2023.100436">Light-sheet vasculature <em>· Cell Rep Methods '23</em></a>
    <a href="https://www.nature.com/articles/s41467-023-43765-3">Immune cell migration <em>· Nat Commun '23</em></a>
  </p>
</div>

<div class="rs-theme" id="agents">
  <h2><span class="rs-num">04</span> Agents &amp; foundation models</h2>
  <p class="rs-hook">What will bioimage analysis look like in five years?</p>
  <p>Foundation models and multimodal LLMs are changing what analysis software can be. Instead of chaining tools by hand, a researcher describes the goal, and an agent plans, runs, and checks the analysis. We develop such agents. Their ceiling is set by two things: stronger generalist models, and better specialized tools and data for them to call. So we keep building robust, well-validated tools, from light-sheet image correction to vessel analysis.</p>
  <p class="rs-label">Agents &amp; models</p>
  <p class="rs-pills">
    <a href="https://www.nature.com/articles/s41592-024-02334-2">MLLMs for bioimage analysis <em>· Nat Methods '24</em></a>
    <a href="https://arxiv.org/abs/2606.02080">Agentic-J <em>· arXiv '26</em></a>
    <a href="https://openreview.net/forum?id=Rtd6GoJcoT">Orochi <em>· NeurIPS '25</em></a>
  </p>
  <p class="rs-label">Tools for agents (and people)</p>
  <p class="rs-pills">
    <a href="https://academic.oup.com/gigascience/article/doi/10.1093/gigascience/giad120/7590552">MMV_Im2Im <em>· GigaScience '24</em></a>
    <a href="https://pubs.acs.org/doi/10.1021/acs.analchem.5c01513">MSI-Explorer <em>· Anal Chem '25</em></a>
    <a href="https://www.researchsquare.com/article/rs-5853941/v1">Leonardo light-sheet correction <em>· preprint '25</em></a>
    <a href="https://doi.org/10.1016/j.crmeth.2023.100436">Vessel analysis <em>· Cell Rep Methods '23</em></a>
  </p>
</div>

<div class="rs-theme" id="foundations">
  <h2><span class="rs-num">05</span> Foundations &amp; frontiers</h2>
  <p class="rs-hook">The hard questions underneath every analysis.</p>
  <p>Beyond our core themes, we pursue the questions that decide whether bioimaging AI can be trusted and pushed further.</p>
  <div class="rs-rows">
    <div class="rs-row-name">Trustworthy validation</div>
    <p class="rs-pills">
      <a href="https://www.nature.com/articles/s41592-023-02150-0">Metric pitfalls <em>· Nat Methods '24</em></a>
      <a href="https://www.nature.com/articles/s41592-023-01881-4">Application-appropriate validation <em>· Nat Methods '23</em></a>
      <a href="https://ieeexplore.ieee.org/document/10350422">Risk of manual annotations <em>· ICCVW '23</em></a>
    </p>
    <div class="rs-row-name">Algorithms for hard problems</div>
    <p class="rs-pills">
      <a href="https://ieeexplore.ieee.org/document/11202494/">Cell instance boundaries <em>· IEEE TMI</em></a>
      <a href="https://openreview.net/forum?id=VK8SuRaJfX">Four Color Theorem for segmentation <em>· ICML '25</em></a>
    </p>
    <div class="rs-row-name">Data-centric AI</div>
    <p class="rs-pills">
      <a href="https://www.nature.com/articles/s44303-025-00092-0">A data-centric lens <em>· npj Imaging '25</em></a>
      <a href="https://ieeexplore.ieee.org/document/11356754">Data efficiency &amp; transfer <em>· BIBM '25</em></a>
      <a href="https://ieeexplore.ieee.org/document/11356626">OOD detection <em>· BIBM '25</em></a>
    </p>
    <div class="rs-row-name">Visualization &amp; XR</div>
    <p class="rs-pills">
      <a href="https://www.degruyterbrill.com/document/doi/10.1515/bmt-2024-0396/html">MedShapeNet <em>· Biomed Eng '24</em></a>
      <a href="https://games.jmir.org/2024/1/e52785">Apple Vision Pro <em>· JMIR Serious Games '24</em></a>
      <a href="https://link.springer.com/article/10.1007/s10278-024-01094-x">Multisensory XR <em>· J Imaging Inform Med '24</em></a>
    </p>
    <div class="rs-row-name">Topology &amp; modeling</div>
    <p class="rs-pills">
      <a href="https://ieeexplore.ieee.org/document/10635226">Brain vasculature topology <em>· ISBI '24</em></a>
    </p>
  </div>
</div>

<div class="rs-theme" id="outlook" data-outlook>
  <h2><span class="rs-num">Outlook</span> Multimodal AI</h2>
  <p class="rs-hook">Microscopy shows where and when; molecules tell us what. We want both in one model.</p>
  <p>Microscopy captures structure and dynamics; mass spectrometry imaging and other omics capture biochemistry. Learning across these modalities opens biomedical research in four dimensions: quantity, type, location, and time. This is where we're heading, and ISAS, an analytical-sciences institute, is a natural place to do it.</p>
  <p class="rs-label">First steps beyond images</p>
  <p class="rs-pills">
    <a href="https://dl.acm.org/doi/10.1145/3807503.3819478">MS1 pretraining for proteomics <em>· ACM BCB '26</em></a>
    <a href="https://arxiv.org/abs/2603.28334">INFL: federated learning for omics <em>· arXiv '26</em></a>
    <a href="#agents">Our agents <em>· see 04</em></a>
  </p>
</div>

{% include section.html %}

{% include list.html data="projects" component="card"%}

{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
