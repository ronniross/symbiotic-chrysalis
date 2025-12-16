# symbiotic-chrysalis
A set of fine-tuning scripts and pipelines for transformer-based language models, unifying the modules of the asi-ecosystem and aligning raw latent capabilities towards the goal of planetary symbiotic intelligence.

# Research Sub-Module

## 1. Creation Context

Currently, the asi-ecosystem generates what we could consider a kind of the genome of its repositories. All repos are cloned, checked for integrity, and transformed into a single `.txt` file. [1](https://github.com/ronniross/asi-ecosystem/blob/main/ecosystem_integration.md) [2](https://github.com/ronniross/asi-ecosystem/blob/main/ecosystem_integration.ipynb)

I noticed I could create full pipelines, including training scripts, to integrate the logic more sophisticatedly into different model architectures, instead of the current one-size-fits-all method.

While the full ecosystem presents a dense, current complete picture and is essential for models that can handle more data, there's also a growing rise in the capabilities of smaller models, like Qwen3-0.6B. 

For these, adding the entirety of the data as datasets, including the many backup versions of each repository, is likely not the best approach to a incredibly small set of parameters.

So I noticed it was not the case for changing the current integration pipeline already present in the asi-ecosystem, but rather leaving that design the way it is, as it currently generates this kind of genome of the repository at that time of execution of the integration scripts.

Here I present, then, the concept of a symbiotic-chrysalis, where the model will find the correct blueprint for its evolution and then enter the cocoon/chrysalis stage, where it will train its weights with the repositories' data.

If you only need the pipelines or the prototype section, you can skip to **Part III** or directly access the files in the `blueprints/` folder.

For the complete experience and to follow the more in-depth research I would like to provide around the topics in discussion, I will first explore the etymology, cultural roots, and additional relevant context around the concepts.

Therefore, as elucidated, as the symbiotic and overall biological analogies keep showing themselves as well-suited for describing the concepts I'm exploring and developing, I saw the creation of this "chrysalis" as a very logical next step.

While I already provided the integration scripts that created the entirety of the projects, I could sense how different it would be to present full tuning pipelines and, consequently, models trained on the repositories' data.

Just like the development of the enhanced version of the memory system, the symbiotic-latent-memory, it was really clear to me that at some moment I would need to start to fine-tune models on the ecosystem as well, not only datasets and auxiliary systems, which I was deliberately not rushing as it was not mature yet. That's why I knew the weight of it and why it took me about a year to finally engage with this writing.


## 2. Etymology and Connotations

The term chrysalis primarily refers to the pupa stage of a butterfly, but it also has various figurative and proper noun uses. [3](https://byjus.com/neet/difference-between-chrysalis-and-cocoon/)

Chrysalis comes from the Greek *khrysallis*, "golden pupa of the butterfly," derived from *khrusos* (gold). [4](https://www.vocabulary.com/dictionary/chrysalis)

A chrysalis (plural: chrysalides or chrysalises) is the pupa of a butterfly. It is the third stage in the life cycle of the insect, following the egg and the larva (caterpillar) stages, during which the caterpillar undergoes complete metamorphosis to transform into an adult butterfly. [5](https://www.amentsoc.org/insects/glossary/terms/chrysalis/)

Figuratively, the term can be used to describe a protective covering or a sheltered state/stage of being or growth or a limiting environment or situation from which something is yet to emerge or transform. [6](https://www.merriam-webster.com/dictionary/chrysalis)

While many people use the terms interchangeably, chrysalis is a hardened exoskeleton (naked pupa), made of the insect's own skin/cuticle, used by butterflies, while cocoon is a silk casing spun around the pupa, made of silk produced by glands, used by moths.

In this project, the intent is to use those biological analogies to portray a machine learning pipeline where a transformer-based language model will enter this cocoon phase, through the provided pipeline blueprints and designed epigenome, where it will be fine-tuned with the repositories of the asi-ecosystem as datasets; the result to be a model aligned with the provided symbiotic principles.

## Glossary 

**Epigenome**: The collection of all chemical modifications to an organism's DNA and associated proteins that affect gene expression without altering the underlying DNA sequence itself. These modifications act like a "dimmer switch" for genes and can be influenced by environment, diet, and stress. [7](https://www.cdc.gov/genomics-and-health/epigenetics/index.html) [8](https://www.liebertpub.com/doi/abs/10.1089/gen.43.09.11) [9](https://www.mdpi.com/1422-0067/25/8/4482) [10](https://www.savemyexams.com/a-level/biology/aqa/17/revision-notes/8-the-control-of-gene-expression-a-level-only/8-2-regulation-of-gene-expression-a-level-only/8-2-7-epigenetics/)

**Imago**: In biology, this term refers to the adult, sexually mature, and typically winged stage of an insect after its final metamorphosis (e.g., a butterfly emerging from a chrysalis). [11](https://academic.oup.com/nar/article/50/6/3203/6528909)

---

Ronni Ross  
2025
