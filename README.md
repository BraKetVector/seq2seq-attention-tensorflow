# seq2seq with attention tensorflow

## Introduction

In this tutorial we will create neural machine translation based on modern 
Attention mechanism Seq2Seq algorithm from scratch. 
There are several tutorial:
> Official TensorFlow Tutorial https://github.com/tensorflow/nmt
> Official PyTorch Tutorial  https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html


But official TensorFlow Tutorial does not cover the realization of attention mechanism 
(using only attention wrapper), and from my opinion it is the main part of 
modern neural translation.  The main idea was to provide a deep tutorial that 
step by step covers all aspect of seq2seq with attention algorithm. 
We we’ll use TensorFlow framework just, because we want to provide 
good implemented and working example based on 
(https://github.com/ematvey/tensorflow-seq2seq-tutorials 
without implementing of attention mechanism) of this idea on low level, 
as good as it was done in original PyTorch tutorial.

![seq2seq-with-attention](pictures/attention_mechanism.jpg)
