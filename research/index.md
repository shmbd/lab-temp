---
title: Research
nav:
  order: 1
  tooltip: Research directions and 85 publications
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Our division connects indigenous microbial isolation and quantitative _in vitro_ characterization with whole-genome sequencing, pangenomics, and biosynthetic gene-cluster (BGC) mining—bridging local microbial biodiversity in Bangladesh with human health, diagnostics, and sustainable industrial bioprocesses.

{%
  include button.html
  icon="fa-solid fa-scroll"
  text="Jump to All 85 Publications"
  link="#all-publications"
%}
{%
  include button.html
  icon="fa-solid fa-graduation-cap"
  text="Division Google Scholar"
  link="https://scholar.google.com/citations?user=v5JwSGwAAAAJ&hl=en"
%}

{% include section.html %}

## Research Directions

{% capture dir1 %}
<div class="mbd-panel" id="probiotics">
  <span class="mbd-kicker">01 · Functional Characterization</span>
  <h3>Probiotics &amp; Functional Health</h3>
  <p>We investigate beneficial microorganisms from indigenous dairy and fermented matrices through taxonomic identification, gastrointestinal survival and safety screening, antioxidant and antidiarrheal evaluation, and comparative genomics—carefully separating <em>in vitro</em> potential from demonstrated clinical effects.</p>
  <ul>
    <li>Indigenous lactic acid bacteria isolation from local dairy and fermented sources</li>
    <li>Bile-salt tolerance, antimicrobial antagonism, safety &amp; resistome screening</li>
    <li>Comparative genomics and pangenome-scale probiotic trait profiling</li>
  </ul>
  <div class="mbd-taxa"><strong>Representative Taxa:</strong> <em>Weissella confusa, Enterococcus lactis, Leuconostoc lactis, Lactiplantibacillus plantarum</em></div>
</div>
{% endcapture %}

{% capture dir2 %}
<div class="mbd-panel" id="discovery">
  <span class="mbd-kicker">02 · Metabolites &amp; Genome Mining</span>
  <h3>Microbial Drug Discovery</h3>
  <p>Our work explores antibacterial isolates and their bioactive secondary metabolites. Whole-genome sequencing and biosynthetic gene-cluster (BGC) analysis frame experimental questions while activity-guided bioassays connect genomic clusters with functional natural products.</p>
  <ul>
    <li>Antimicrobial and antibiofilm screening of environmental &amp; marine-associated isolates</li>
    <li><em>In silico</em> BGC and CAZyme repertoire mining across actinomycetes and myxobacteria</li>
    <li>Druggable proteome and immunopharmacoinformatics target prioritization</li>
  </ul>
  <div class="mbd-taxa"><strong>Representative Taxa:</strong> <em>Streptomyces spp., Corallococcus, Salinispora, Pseudomonas aeruginosa, Bacillus subtilis</em></div>
</div>
{% endcapture %}

{% include cols.html col1=dir1 col2=dir2 %}

{% capture dir3 %}
<div class="mbd-panel" id="genomics">
  <span class="mbd-kicker">03 · WGS &amp; Bioinformatics</span>
  <h3>Genomics &amp; Microbial Surveillance</h3>
  <p>Whole-genome, pangenomic, and molecular approaches support the study of microbial function, viral evolution, and antimicrobial resistance (AMR). Bioinformatics links sequence data to molecular diagnostics, electrochemical nanobiosensors, and pathogen surveillance.</p>
  <ul>
    <li><em>De novo</em> genome assembly, comparative pangenomics &amp; virulence mapping</li>
    <li>Multidrug-resistant (MDR) and ESBL pathogen surveillance in clinical &amp; food systems</li>
    <li>Viral complete-genome phylogenomics &amp; graphene/aptamer electrochemical biosensors</li>
  </ul>
  <div class="mbd-taxa"><strong>Representative Targets:</strong> <em>Citrobacter werkmanii NIB003, Salmonella, Klebsiella pneumoniae, Providencia stuartii, HBV</em></div>
</div>
{% endcapture %}

{% capture dir4 %}
<div class="mbd-panel" id="industry">
  <span class="mbd-kicker">04 · Industrial Biotechnology</span>
  <h3>Enzymes &amp; Sustainable Bioenergy</h3>
  <p>The division optimizes extracellular microbial biocatalysts for eco-friendly industrial bioprocessing and investigates electrogenic bacterial consortia in microbial fuel cells (MFCs) for waste-to-energy conversion and environmental remediation.</p>
  <ul>
    <li>Bioprocess optimization &amp; purification of alkaline proteases, keratinases, amylases &amp; cellulases</li>
    <li>Enzymatic leather dehairing and tannery/industrial effluent quality assessment</li>
    <li>Electrogenic bacteria isolation &amp; proton-exchange membrane MFC evaluation</li>
  </ul>
  <div class="mbd-taxa"><strong>Representative Taxa:</strong> <em>Bacillus licheniformis, Bacillus amyloliquefaciens, Arthrobacter sp. NFH5, Aeromonas hydrophila</em></div>
</div>
{% endcapture %}

{% include cols.html col1=dir3 col2=dir4 %}

{% include section.html %}

## How Wet Lab & Dry Lab Connect

{% capture step1 %}
#### 01 · Isolate
Targeted bioprospecting of bacteria from indigenous dairy foods, soils, riverine ecosystems, clinical samples, and industrial effluents across Bangladesh.
{% endcapture %}

{% capture step2 %}
#### 02 · Characterize
Quantitative _in vitro_ evaluation of gastrointestinal resilience, antimicrobial activity, extracellular enzyme kinetics, and bioelectrochemical performance.
{% endcapture %}

{% capture step3 %}
#### 03 · Understand
Whole-genome assembly, pangenome architecture, AMR/virulence profiling, and secondary-metabolite BGC & CAZyme genome mining.
{% endcapture %}

{% include cols.html col1=step1 col2=step2 col3=step3 %}

{% include section.html %}

## Highlighted

{% include citation.html lookup="doi:10.1007/s12602-025-10775-0" style="rich" %}

{% include citation.html lookup="doi:10.1016/j.microb.2025.100562" style="rich" %}

{% include citation.html lookup="doi:10.1007/s11756-025-01866-y" style="rich" %}

{% include citation.html lookup="doi:10.1016/j.jgeb.2025.100508" style="rich" %}

{% include section.html %}

## All Publications
{:#all-publications}

Search and filter **85 scholarly records** (72 journal & conference papers, 8 book chapters, and 5 preprints spanning 2013–2026) by keyword, author name, journal, year, or topic tag.

{% include search-box.html %}

{% include tags.html tags="probiotics, genomics, biosensors, microbial-enzymes, microbial-fuel-cells, amr, drug-discovery, virology, book-chapter, preprint" link="research" %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
