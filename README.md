## Kubeflow Tutorial 

### Introduction
This project was initially designed as a preparation for idalab's kubeflow workshop, which consists of:
- Introduction to basic concepts of K8S and Kubeflow
- Instructions of creating a Kubeflow notebook server
- Example notebook for deploying a pipeline with jupyterlab extension Kale

We used CLI `claat` (CodeLabs as a Thing) to convert Google Docs into html with a built-in CodeLabs format.
To install claat, simply run (if you have go installed):
```
go get github.com/googlecodelabs/tools/claat
```
or download the pre-compiled binary https://github.com/googlecodelabs/tools/releases/tag/v2.2.0.

To convert Google Doc contents into CodeLabs formats run:
```
claat serve <doc-id>
```

### Run a Pipeline 
Install the project:
```
git clone https://github.com/idalab-de/kube-tutorial.git
cd kube-tutorial/pipeline
```
The example notebook for building a Kubeflow pipeline can be found under the name `analytics.ipynb`