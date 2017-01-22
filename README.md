# CaffeModelFileParser

# Overview
Parser helps to extract Layer information, Weights and Bias of each layers from .caffeodel file.
This helps in implementing classifying/inferencing on VPU's

# Script
Python CaffemodelParser.py  "path 2 deploy.prototxt file"  "path 2 .caffemodel file"

# Output
* LayerName: Name of the Layer
* Weights: Layer Weight Matrix
* Bias : Layer Bias Matrix


