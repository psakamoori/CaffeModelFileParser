# CaffeModelFileParser

# Overview
Parser the .caffemodel file to extract Layer information, Weights and Bias of each layers.
This helps in implementing classifying/inferencing on VPU's

# Script
Python CaffemodelParser.py  "path to deploy.prototxt file"  "path to .caffemodel file"

# Output
* LayerName: Name of the Layer
* Weights: Layer Weight Matrix
* Bias : Layer Bias Matrix


