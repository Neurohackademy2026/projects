# NeuroHackademy 2026 project directory

## Projects

<!-- 
INSTRUCTIONS: COPY THE EXAMPLE BELOW AND REPLACE ALL THE ITEMS BETWEEN TRIPLE-DASHES ("---") WITH YOUR PROJECT INFORMATION 
-->

### ---Project title---
**Description**: ---Your description here ---\
**Project url**: ---Your URL here ---\
**Contributors**: [---Name 1---](---GitHub link 1---) & [---Name 1---](---GitHub link 1---)

### Self-supervised deep learning for Structure-to-Function Prediction in Visual Cortex
**Description**: Deep learning models for the construction of retinotopic maps from structural data have achieved promising results, but they still struggle at capturing fine-grained individual differences and generalising across datasets.
We hypothesise that these struggles can partially be attributed to the limited number of samples available to train these models in fully supervised models.
Self-supervised learning, where the model is first trained to learn a general representation of the phenomenon of interest on unlabelled data that can later be fine-tuned for the task of interest, can alleviate this problem, as large, heterogeneous collections of unlabelled structural data are now available
This project therefore aims at exploring the feasibility of this approach for retinotopy maps modelling by
1) Defining a transformer model that can be trained in a self-supervised manner on the HCP structural data.
2) Fine-tune the resulting model to predict retinotopy maps from structural data.
We aim for a fully functioning pipeline that can be further extended in future works.\

**Project url**: https://github.com/Junebeomstics/surface-vision-transformers \

**Contributors**: [Junbeom Kwon](https://github.com/Junebeomstics) & [Federico Giacardi](https://github.com/federicogiacardi01)  


### Perception vs. Imagery: An Exploratory Analysis with NSD-Imagery Data
**Description**: Using RSA and brain encoding model to study the differences in brain responses during perception and imagery.  \
**Project url**: https://github.com/mynanshan/NHprojectNSDimagery \
**Contributors**: [mynanshan](https://github.com/mynanshan)
<!-- & [Tamar Japaridze](tbd) & [Tong Le Cai](tbd) & [ap](tbd) -->

### Precision fMRI for Multivariate Analysis
**Description**: Precision fMRI uses resting-state data to define individualized functional network. One of the benefits of individualized network definition is that it elegantly handles regions whose functional organizations have huge across-subject variability, region such as the Default Mode Network (DMN). The current project attempts to run multivariate analysis during task fMRI using template/group/individual network definition, and quantify the benefit of precision fMRI for the purpose of multivariate analysis. The current project uses PAN Dataset. \
**Project url**: https://github.com/henrfo/panmvpa \
**Contributors**: [Tong-Le Cai](https://github.com/tonglecai) & [Kareem Al-Khalil](https://github.com/kalkhalil-cmd) & [DT Nguyen](https://github.com/dawntnguyen) & [Sophia Martin](https://github.com/smartin347) & [Henrik Formoe](https://github.com/henrfo) & [Ziyuan Chen]()

### Neuroimaging Data Quality Assurance Open Resource
**Description**: An open-source educational platform dedicated to improving data quality in fMRI and EEG research. Through accessible explanations, annotated examples of common artifacts, practical quality-assurance workflows, and carefully curated learning resources, the project helps students and researchers build the skills needed to recognize, evaluate, and address data-quality issues. By combining education with practical guidance, the website aims to make neuroimaging quality assurance more transparent, consistent, and approachable for the broader research community! \
**Project URL**: [NeuroQA](https://github.com/henrfo/VisualQA) \
**Contributors**: [Tien Yang](https://github.com/tti-yang) & [Morgan Barnes](https://github.com/morganbarnesga) & [Chenye Bao](https://github.com/Psycheyi) & [Henrik Formoe](https://github.com/henrfo) & [Tamaya Levy](https://github.com/tamayalevy) \

### neurolabel
**Description**: A python package for anatomical labeling, functional decoding, and interactive exploration of brain parcellations. Additional features include summarization of statistical brain maps using a parcellation. \
**Project url**: https://github.com/amishavyas/neurolabel \
**Contributors**: [Amisha Vyas](https://github.com/amishavyas), [Mia Casburn](https://github.com/miacasburn), [Hyesun Choi](https://github.com/hyesunchoi1101), [Anna Isberg](https://github.com/aeisberg), [Alex Litovchenko](https://github.com/alitovchenko), [Kaitlyn Mundy](https://github.com/mundy-k), [Rajikha Raja](https://github.com/rajikha), [Lara Ressin](https://github.com/LaraRessin), & [America Romero](https://github.com/romeroamerica)

### nh26_td_gamb_diff_FC_best
**Description**: Predict delay discounting (as measured by questionnaire) from gambling task functional connectivity OR brain structure (DWI) \
**Project url**: https://github.com/pganon32/nh26_td_gamb_diff_FC_best \
**Contributors**: [Jonas Granzow](https://github.com/BalkingTrain), [Caroline Raymond](https://github.com/cbr4zd), [Daniel Porta-Casteras](https://github.com/DCasteras), [Emily Wertheimer](https://github.com/Emily-Wertheimer), [Youngeun Park](https://github.com/graceypark), [Hamid Hemmatr](https://github.com/Imaginglogic), [Jessica Tai](https://github.com/jessie-t8), [Pouneh Baniasad](https://github.com/pouneh-baniasad), [Patrick Gagnon](https://github.com/pganon32)

### Whole-Brain Dynamical Modeling of Attractor Landscapes in Functional Brain Activity
**Description**: Use psilocybin dataset to estimate brain state dynamics using HMMs, as well as attractor landscapes and key features to distinguish altered from normal states \
**Project url**: [FunctionalAttractors](https://github.com/danielcbzn/neurohackademy_group-project) \
**Contributors**: [Monica Vogel](https://github.com/monicajvogel), [Daniel Bazan](https://github.com/danielcbzn), [Yicheng Zheng](https://github.com/zheng1ch), [Donisha Smith](https://github.com/donishadsmith) & [Udbhav Singhal](https://github.com/udusp)

### Predicting Magnetic Resonance Spectroscopy from Functional Connectivity
**Description**: Brain function emerges from the interaction between local neurochemical signaling and large-scale network dynamics. While Magnetic Resonance Spectroscopy (MRS) quantifies the biochemical substrates of neuronal and glial function within specific brain regions, functional MRI reveals how these regions interact as distributed networks to support cognition and behavior. Combining MRS with functional connectivity therefore provides a powerful multiscale framework for understanding how regional excitatory-inhibitory balance, neuronal health, and metabolic processes shape the architecture and efficiency of functional brain networks. This integrated approach moves beyond describing brain activity to elucidating the neurochemical mechanisms underlying network organization and dysfunction.

This project therefore aims to explore the feasibility of this approach by
1) Utilizing the HCP-aging dataset to build baseline regression models for MRS prediction.
2) Using linear mixed models (LMM) and Generalized Estimating Equations (GEE) to test if longitudinal scans do better than baseline data.
We aim for a fully functioning pipeline that can be further extended in future works.\

**Project url**: github.com/prank24/neurohackademy_project_mrs_func \
**Contributors**: [Siddharth Nayak](github.com/SiddharthNayak) & [Prankur Saxena](github.com/prank24) & [Maria Perica](github.com/maria-perica) & [Poorvi Balaji](github.com/poorvi-balaji) & [anca.e.p]
