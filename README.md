# Project Knowledge Extraction and Recommendation System 📚🤖

## Overview

This GitHub repository contains the code and documentation for a comprehensive project aimed at extracting and structuring knowledge from Project Management Institute (PMI)'s Practice Standard for Project Risk Management and the Project Management Body of Knowledge (PMBOK). The project utilizes natural language processing (NLP) techniques and regular expressions to transform unstructured information into a structured framework. Additionally, a knowledge-based recommendation system has been implemented to provide valuable insights for project and risk management professionals.

## Table of Contents

- [Project Overview](#project-knowledge-extraction-and-recommendation-system-)
- [Table of Contents](#table-of-contents)
- [General Context](#i-general-context)
  - [Introduction](#introduction)
  - [Problem Description](#problem-description)
  - [Methodology](#methodology)
- [Data Extraction and Preprocessing](#ii-data-extraction-and-preprocessing)
  - [PMBOK](#1-pmbok)
  - [Practice Standard for Project Risk Management](#2-practice-standard-for-project-risk-management)
  - [Merging Dataframes](#3-merging-both-dataframes)
- [Modeling the Graph](#iii-modeling-the-graph)
- [Implementation of the Knowledge-based Recommendation System](#iv-implementation-of-the-knowledge-based-recommendation-system)


## I. General Context

### Introduction

The project focuses on transforming unstructured information from PMBOK and PMI's Practice Standard for Project Risk Management into a structured framework using NLP and regular expressions. The ultimate goal is to create a knowledge repository and a recommendation system for project and risk management professionals.

### Problem Description

Effective project risk management is crucial, but existing documents lack a clear structure. The project addresses this by creating a structured framework to enhance knowledge extraction and accessibility.

### Methodology

A systematic approach involving data collection, preprocessing, NLP techniques, and the creation of a conceptual graph is detailed. The report emphasizes subject matter expert validation for quality assurance.

## II. Data Extraction and Preprocessing

### 1. PMBOK

#### Data Workflow for Text Data Preparation

- Extracting section titles from the PDF
- Conversion of PDF to text format for accurate content extraction
- Extraction and structuring of section content
- Data cleaning and preprocessing
- Adding new columns (References, Figures/Tables, Type, etc.)
- Visualizing topics using PyLDAvis

### 2. Practice Standard for Project Risk Management

#### Data Workflow for Text Data Preparation

- Extracting images
- Preprocessing chapters and text extraction
- Appendices text extraction and content cleaning
- Merging both dataframes

## III. Modeling the Graph

- Extracting taxonomic and non-taxonomic relations
- Constructing a graph using NetworkX and Matplotlib
- Feature engineering and implementing a Graph Neural Network architecture

## IV. Implementation of the Knowledge-based Recommendation System

- Data preprocessing
- Implementing the model using TensorFlow's Keras API
- Model evaluation and accuracy evolution
