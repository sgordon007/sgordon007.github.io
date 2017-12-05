---
layout: page
title: Research
---

## Polyploid Genome Assembly

Polyploid plants are often larger, more productive and more stress tolerant than their diploid progenitors. Thus, it is not surprising that many highly productive crops are fairly recent allopolyploids (e.g. wheat, strawberry, coffee, cotton). Unfortunately, it is notoriously difficult to assemble high-quality genomes for polyploids due to the presence of highly similar copies of sequences throughout the genome.
We recently made an enormous computational breakthrough that allows us to partition sub-genomes of allopolyploid species without any prior information or supervision and with nearly perfect precision and recall (Gordon et al., manuscript in preparation). In fact, this algorithm can inform whether a set of DNA sequences are derived from an allopolyploid in the first place. 

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "polyploid" %}
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
{% if pub.project == "pangenomics" %}
  {{ pub.content }}
{% endif %}
{% endfor %}


## Comparative genomics approach to study the genetic basis for annual/perennial life history transitions over evolutionary time

Annual versus perennial growth of plants is a complex trait that has presumably co-evolved with other functional characteristics of an organism in response to a particular environment. The genetic determinants of annual versus perennial life history strategy are largely unknown. 

My work developing resources for Brachypodium sylvaticum led to an approved FY2017 JGI CSP grant to sequence many additional annual and perennial species within the genus. The strategy is to use the fact that annual/perennial transitions have occurred at multiple nodes in the tree of this genus and identify candidate genetic correlates common to those events but not found at other speciation events. I plan to continue to collaborate on this project and may pursue other funding.

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "perennial" %}
  {{ pub.content }}
{% endif %}
{% endfor %}


## Brachypodium distachyon as a model for grass biology

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "distachyon" %}
  {{ pub.content }}
{% endif %}
{% endfor %}


## Comparative genomics of fungi

### Recent Publications
{% for pub in site.publications reversed %}
{% if pub.project == "fungi" %}
  {{ pub.content }}
{% endif %}
{% endfor %}

 