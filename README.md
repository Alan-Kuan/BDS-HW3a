# Stage-A Document Intelligence

## Screenshots
- the Web UI
  - ![screenshot-1](images/screenshot-1.png)
- display progress
  - ![screenshot-2](images/screenshot-2.png)

## Overview
![overview of the work](images/overview.png)

## Installation

```bash
conda create -n docint python=3.11
conda activate docint
conda install -c conda-forge ghostscript
pip install -r requirements.txt
```

## How to Start?
```bash
streamlit run main.py
```

## Target

Create an artificial intelligence that searches in which table in the given pdf files has the desired information.  

#### Input

1. pdf files with only tables inside
2. the searching keywords

#### Output

**the hole table with desired information in it**

#### Example

The given pdf file:  
![image](https://github.com/Stage-A/Document-Intelligence/blob/main/images/example1.png)
Search query:  

```commandline
非監督式學習的應用
```

Output:
![image](https://github.com/Stage-A/Document-Intelligence/blob/main/images/example2.png)

## How to contribute

* Every one finishes the whole project and pulls the requests , do not edit the main branch
* if your code is acceptable, we will add it into the main branch

## Background Knowledge

[Azure Document Intelligence]( https://azure.microsoft.com/en-us/products/ai-services/ai-document-intelligence
)

## Test Document

[Document 1](https://docs.google.com/document/d/1Di5oVYhUF6p-zj2y0DEBBeTvhC91KhX8/edit?usp=sharing&ouid=107784913306655694785&rtpof=true&sd=true)
[Document 2](https://docs.google.com/document/d/1HiZrgIyvwY8Fi4eLS0QGUkkycngtD6XJ/edit?usp=sharing&ouid=107784913306655694785&rtpof=true&sd=true)
