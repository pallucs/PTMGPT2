<h1>PTMGPT2</h1> <a href="https://zenodo.org/doi/10.5281/zenodo.12655680"><img src="https://zenodo.org/badge/758635995.svg" alt="DOI"></a> 
<p>Here, we introduce PTMGPT2, a suite of models capable of generating tokens that
signify modified protein sequences, crucial for identifying PTM sites. At the core of this
platform is PROTGPT2, an autoregressive transformer model. We have adapted
PROTGPT2, utilizing it as a pre-trained model, and further fine-tuned it for the spe
cific task of generating classification labels for a given PTM type. Uniquely, PTMGPT2
utilizes a decoder-only architecture, which eliminates the need for a task-specific clas-
sification head during training. Instead, the final layer of the decoder functions as a
projection back to the vocabulary space, effectively generating the next possible token
based on the learned patterns among tokens in the input prompt.</p>
<h3>PTMGPT2 model and workflow</h3>
<img src='PTMGPT2-workflow-model.png'></img>

<h3>Download sample model for inference</h3>
<p>Link - (https://nsclbio.jbnu.ac.kr/GPT_model/)</p>
<p>Contact us directly at <b>palisthashrestha7@jbnu.ac.kr</b> for bulk predictions and trained models</p>

<h3>PTMGPT2 Webserver</h3>
<p>Link - (https://nsclbio.jbnu.ac.kr/tools/ptmgpt2/)</p>

<h3>PTMGPT2 Models</h3>
<p>Link - (https://doi.org/10.5281/zenodo.11371883)</p>
<p>Link - (https://zenodo.org/records/11362322)</p>

<h3>PTMGPT2 Datasets</h3>
<p>Link - (https://doi.org/10.5281/zenodo.11377398)</p>

<h3>Requirements</h3>
<p>python 3.11.3 <br> transformers 4.29.2 <br> scikit-learn 1.2.2 <br> pytorch 2.0.1 <br> pytorch-cuda 11.7</p>

<h3>Basic Usage</h3>
<p>• Model: This folder hosts a sample model designed to predict PTM sites from given
protein sequences, illustrating PTMGPT2’s application.<br>
• Tokenizer: This folder contains a sample tokenizer responsible for tokenizing
protein sequences, including handcrafted tokens for specific amino acids or motifs.<br>
• Inference.ipynb: This file provides executable code for applying PTMGPT2 model
and tokenizer to predict PTM sites, serving as a practical guide for users to apply
the model to their datasets.</p>





