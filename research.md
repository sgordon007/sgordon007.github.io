---
layout: page
title: Research
---

## Polyploid Genome Assembly

Polyploid plants are often larger, more productive and more stress tolerant than their diploid progenitors. Thus, it is not surprising that many highly productive crops are fairly recent allopolyploids (e.g. wheat, strawberry, coffee, cotton). Unfortunately, it is notoriously difficult to assemble high-quality genomes for polyploids due to the presence of highly similar copies of sequences throughout the genome.
We recently made an enormous computational breakthrough that allows us to partition sub-genomes of allopolyploid species without any prior information or supervision and with nearly perfect precision and recall (Gordon et al., manuscript in preparation). In fact, this algorithm can inform whether a set of DNA sequences are derived from an allopolyploid in the first place. 

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "traits" %}
  {{ pub.content }}
{% endif %}
{% endfor %}

## Comparative Genomics 

In our disease research, we focus on the ecology and evolution of wildlife disease reservoirs with implications for human and domestic animal health.  Highly virulent diseases induce high mortality in their hosts and thus decimate host populations. How do such virulent diseases persist and spread despite wiping out the hosts they rely upon? Our work investigates how ecological and evolutionary mechanisms, particularly spatial and temporal host refuges and pathogen reservoirs, enhance persistence using plague, bat diseases, and avian influenza as example systems.

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "disease" %}
  {{ pub.content }}
{% endif %}
{% endfor %}

## High throughput pan-genomics of eukaryotic species. 

Although not well recognized, individuals and sub-populations of a single species can vary in the presence/absence of genes and other functional sequences (not just alleles).
undertook the ambitious goal to determine just how large a eukaryotic pan-genome might be. 
We de novo assembled and annotated complete genomes for 54 genetically and geographically diverse inbred lines of the model grass Brachypodium distachyon.
This work yielded a pan-genome containing nearly twice the number of genes found in any individual genome (Gordon et al., 2017, Nature Communications, in press). Interestingly, of genes that were differentially present among the species-wide pan-genome, many were present in all sampled individuals of certain sub-populations and may be important for adaption to local geographic conditions as well as contributing to the population structure itself.

Currently we are developing PanHipMer to support pan-genomics analyses involving thousands of genomes. To achieve this, we are incorporating annotation and comparative genomics in the assembly process. 

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "livestock" %}
  {{ pub.content }}
{% endif %}
{% endfor %}

## Other

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "other" %}
  {{ pub.content }}
{% endif %}
{% endfor %}
