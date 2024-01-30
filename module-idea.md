# Ideas for Modules (M) and Lessons (L) for Infusing FAIR Principles into Materials Science

## M+: Software Carpentry and Data Management Related Tools

programming, version control, unix shell for automating tasks, database tools for programmatic data access interaction and  labbook for documenting science

#### Potential resources: 

- https://swcarpentry.github.io/shell-novice
- https://swcarpentry.github.io/python-novice-gapminder
- https://swcarpentry.github.io/sql-novice-survey/
- https://swcarpentry.github.io/git-novice
- https://www.writethedocs.org/

## M0: World beyond spreadsheets and metadata in filenames 

### L1: data formats for machine-readable data (CSV, JSON, XML for materials data)

#### Motivating examples:
- https://www.youtube.com/watch?v=N2zK3sAtr-4
- “The Semantic Web” from Scientific American 284(5): 28–37, 2001
- http://tinyurl.com/vxk2s9kb
 
### L2: Introduction to knowledge representation: data + metadata

introducing structure and syntax into the data or how to make the data machine-actionable through self-describing key/value data structure (e.g., XML, JSON with semantically relevant key names)

#### Potential resources: 

- https://carpentries-incubator.github.io/scientific-metadata/index.html
- https://github.com/marda-alliance/FAIR_2023_Workshop/ 
  (tabular data, data documents)

### L3: Prepare your first dataset and code repository 

(git or zenodo, jupyterlab vs notebook) and pay attention to documentation (https://www.writethedocs.org/)

### L4: Verify if data is well structured for correctness - schema and schema validators


## M1: Data reuse (use prior data from last year's course/literature/database) 

### L1: Work with data from prior work or last year course (CSV, JSON, XML)

(load data, and visualize it using the script (python/matplotlib, gnuplot) – write notebook to capture the workflow) 

#### Potential resources:

- https://swcarpentry.github.io/python-novice-gapminder/

### L2: Use REST API (Materials Project, Citirination, AWFLOW)

### L3: Data scraping and data restructuring 

(e.g., Beautiful Soup for XML and HTML documents in Python, rvest and xml2 in R) 

## M2: Data integration (taking data from other groups/work, integrate experimental and computational work)

### L1: Data cleaning

#### Potential resources:

- tool OpenRefine https://librarycarpentry.org/lc-open-refine/01-introduction.html

### L2: Data integration: metadata standardization challenges (dealing with synonymous and homonymous terms, singular/plural word forms, lexical/dialectical variants...)

#### Potential resources:

- https://www.yamz.net/ 
- YAMZ in materials science: https://doi.org/10.1162/dint_a_00211

### L3: Knowledge representation

data + metadata + rules - adding semantics to structure and syntax: Resource Description Framework (RDF) and schema (RDFS), database and ontology

#### Potential resources:

- https://github.com/marda-alliance/FAIR_2023_Workshop/ 
- (tabular data, documents, knowledge graphs)

#### Manufacturing ontologies:

- https://matportal.org/, 
- https://terminology.nfdi4ing.de/ts/

#### Mechanical testing ontologies:

- https://doi.org/10.1016/j.compind.2023.104016
- https://github.com/emmo-repo/domain-mechanical-testing/blob/master/emmo-mechanical-testing.owl

## M3: FAIR data generation 

### L1: Generate data with metadata 

### L2: Generate data with metadata and annotate with existing ontology/vocabulary

### L3: Prepare FAIR publication 

(publication space: zenodo, MDF), or plan for effortless and reproducible work: describe a computational/experimental environment, provide notebook as an essay/journal article, plan for incremental work.

## Other resources

- https://github.com/Materials-Data-Science-and-Informatics/awesome-fair
- https://github.com/tilde-lab/awesome-materials-informatics (see standarization initiatives)
- https://howtofair.dk/
- https://codemeta.github.io/user-guide/
- https://github.com/marda-alliance/FAIR_2023_Workshop/ 
- https://open.hpi.de/courses/semanticweb2016/overview
- https://librarycarpentry.org/Top-10-FAIR/
- Shanahan, H., Hoebelheinrich, N. and Whyte, A., 2021. Progress toward a comprehensive teaching approach to the FAIR data principles. Patterns, 2(10).
- https://openscience101.org/
- https://nasa.github.io/Transform-to-Open-Science/

