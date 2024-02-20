<h1>PTMGPT2</h1>
<p>PTMGPT2 is a suite of models capable of generating tokens
that signify modified amino acid residues, crucial for identifying PTM sites. At the
core of this platform is PROTGPT2, an autoregressive transformer model, origi-
nally trained on 50 million non-annotated sequences spanning the complete spectrum
of the protein space. We have adapted PROTGPT2, utilizing it as a pre-trained
model, and further fine-tuned it for the specific task of generating classification
labels for a given protein sequence. Uniquely, PTMGPT2 employs a zero-shot text
classification approach using a generative language model, negating the need
for task-specific classification heads.</p>
<h3>PTMGPT2 model and workflow</h3>
<img src='PTMGPT2-workflow-model.png'></img>

<h3>Download sample model for inference</h3>
<p>Link - (https://nsclbio.jbnu.ac.kr/GPT_model/)</p>
<p>Contact us directly at <b>palisthashrestha7@jbnu.ac.kr</b> for bulk predictions and trained models</p>

<h3>PTMGPT2 Webserver</h3>
<p>Link - (https://nsclbio.jbnu.ac.kr/tools/ptmgpt2/)</p>

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





