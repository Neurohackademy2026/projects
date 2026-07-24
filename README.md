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
**Description**: Using RSA and brain encoding model to study the differences in brain responses during perception and imagery. \
**Project url**: https://github.com/mynanshan/NHprojectNSDimagery \
**Contributors**: [Muye Nanshan](https://github.com/mynanshan)
<!-- & [Tamar Japaridze](anonymous) & [Tong Le Cai](anonymous) & [ap](anonymous) -->

### Precision fMRI for Multivariate Analysis
**Description**: Precision fMRI uses resting-state data to define individualized functional network. One of the benefits of individualized network definition is that it elegantly handles regions whose functional organizations have huge across-subject variability, region such as the Default Mode Network (DMN). The current project attempts to run multivariate analysis during task fMRI using template/group/individual network definition, and quantify the benefit of precision fMRI for the purpose of multivariate analysis. The current project uses PAN Dataset. \
**Project url**: https://github.com/henrfo/panmvpa \
**Contributors**: [Tong-Le Cai](https://github.com/tonglecai) & [Kareem Al-Khalil](https://github.com/kalkhalil-cmd) & [DT Nguyen](https://github.com/dawntnguyen) & [Sophia Martin](https://github.com/smartin347) & [Henrik Formoe](https://github.com/henrfo) & [Ziyuan Chen]()

### Neuroimaging Data Quality Assurance Open Resource
**Description**: An open-source educational platform dedicated to improving data quality in fMRI and EEG research. Through accessible explanations, annotated examples of common artifacts, practical quality-assurance workflows, and carefully curated learning resources, the project helps students and researchers build the skills needed to recognize, evaluate, and address data-quality issues. By combining education with practical guidance, the website aims to make neuroimaging quality assurance more transparent, consistent, and approachable for the broader research community! \
**Project URL**: [NeuroQA](https://github.com/henrfo/VisualQA) \
**Contributors**: [Tien Yang](https://github.com/tti-yang) & [Morgan Barnes](https://github.com/morganbarnesga) & [Chenye Bao](https://github.com/Psycheyi) & [Henrik Formoe](https://github.com/henrfo) & [Tamaya Levy](https://github.com/tamayalevy) & [Merel van der Thiel](https://github.com/merelvdthiel) 

### neurolabel
**Description**: A python package for anatomical labeling, functional decoding, and interactive exploration of brain parcellations. Additional features include summarization of statistical brain maps using a parcellation. \
**Project url**: https://github.com/amishavyas/neurolabel \
**Contributors**: [Amisha Vyas](https://github.com/amishavyas), [Mia Casburn](https://github.com/miacasburn), [Hyesun Choi](https://github.com/hyesunchoi1101), [Anna Isberg](https://github.com/aeisberg), [Alex Litovchenko](https://github.com/alitovchenko), [Kaitlyn Mundy](https://github.com/mundy-k), [Rajikha Raja](https://github.com/rajikha), [Lara Ressin](https://github.com/LaraRessin), & [America Romero](https://github.com/romeroamerica)

### How to predict temporal discounting
**Description**: Predict delay discounting (as measured by questionnaire) from gambling task functional connectivity OR brain structure (DWI) \
**Project url**: https://github.com/pganon32/nh26_td_gamb_diff_FC_best \
**Contributors**: [Jonas Granzow](https://github.com/BalkingTrain), [Caroline Raymond](https://github.com/cbr4zd), [Daniel Porta-Casteras](https://github.com/DCasteras), [Emily Wertheimer](https://github.com/Emily-Wertheimer), [Youngeun Park](https://github.com/graceypark), [Hamid Hemmatr](https://github.com/Imaginglogic), [Jessica Tai](https://github.com/jessie-t8), [Pouneh Baniasad](https://github.com/pouneh-baniasad), [Patrick Gagnon](https://github.com/pganon32)

### Whole-Brain Dynamical Modeling of Attractor Landscapes in Functional Brain Activity
**Description**: Use psilocybin dataset to estimate brain state dynamics using HMMs, as well as attractor landscapes and key features to distinguish altered from normal states \
**Project url**: [FunctionalAttractors](https://github.com/danielcbzn/neurohackademy_group-project) \
**Contributors**: [Monica Vogel](https://github.com/monicajvogel), [Daniel Bazan](https://github.com/danielcbzn), [Yicheng Zheng](https://github.com/zheng1ch), [Donisha Smith](https://github.com/donishadsmith) & [Udbhav Singhal](https://github.com/udusp)

### Hyperface: Modelling the Dynamic Localizer Task
**Description**: Analyze fMRI data from 21 participants, beginning with a first-level general linear model, followed by whole-brain and ROI-specific representational similarity analysis approaches, to compare neural representations of different stimuli types.
**Project url**: https://github.com/LuciZR/Hyperface-Dynamic-Task-Localizer
**Contributors**: [Lucia Z-Rivera](https://github.com/LuciZR), [Jillian O'Malley](https://github.com/jomalle), [Bailey Harris](), [Natalia Pallis-Hassani](), [Heather Laurel Jensen](https://github.com/heatherlaureljensen), & [Emily Fitzgerald]()

### Structural and Functional Connectivity of Face Recognition Pathways
**Description**: Most insights from white matter connectivity needed for face perception come from brain lesioned patients. Yet, there is an opportunity to reproduce the same insights by using big data coming from healthy adults. The Human Connectome Project (HCP) data allows us to do just that, by correlating face memory performance with statistics from reconstructed tracts. This project aimed at correlating face memory performance of HCP participants with their structural and functional connectomes. Structural connectivity was estimated from the stream line counts between ROIs, and also from the track profiles. Functional connectivity was estimated from two types of tasks: resting state (rs), and blocks where faces were shown to participants (task). \
**Project url**: [Structural and Functional Connectivity of Face Recognition Pathways](https://github.com/emiliazms19/Neurohack_project_HCP)\
**Contributors**: [Manuel Mejia](https://github.com/mmejia23), [Ryan Dean](https://github.com/ryan-dean-wustl), [Celina Alba](https://github.com/duncan-lab), [Emilia Zaldivar](https://github.com/emiliazms19), [Chenyuan Li](https://github.com/lichenyuanidt98), [Nick Wellman](https://github.com/nwellman13) & [Shivaram Karandikar](https://github.com/shivaram-k)

### Why Neuroscience
**Description**: Film \
**Project url**: https://youtu.be/82dTs6mZ7XM \
**Contributors**: [Henrik Formoe](https://github.com/henrfo), [Daniel Porta-Casteras](https://github.com/DCasteras), [Lara Ressin](https://github.com/LaraRessin), [Kelly Chang](https://github.com/kellychang4) & [John Pyles](https://github.com/jpyles)

## Exploring Naturalistic Brain Responses with StudyForrest
**Description**: This project explores the StudyForrest dataset, in which participants experience the *Forrest Gump* movie during fMRI. Our team develops preliminary brain encoding and decoding analyses that relate time-varying movie information—such as emotion, audiovisual content, and behavioural annotations—to brain responses. We use the dataset's shared naturalistic stimulus, anatomical derivatives, and multi-subject recordings to study both within-participant and cross-participant representations.
**Project url**: [ForrestGump-NeuroHackademy](https://github.com/JoosenLi/ForrestGump-NeuroHackademy)\
**Contributors:** [tamarj8592](https://github.com/tamarj8592), [juz031](https://github.com/juz031), [joosenli](https://github.com/joosenli), [Konstantinos14](https://github.com/Konstantinos14), [samtorrisi](https://github.com/samtorrisi), [rcastolayo](https://github.com/rcastolayo), and [snpushpi](https://github.com/snpushpi).
