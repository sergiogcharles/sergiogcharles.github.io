---
layout: page
title: Transformer Positional Encoding & Tokenization Study
description: In our study, we investigated the effect of different positional encoding schemes (learned, sinusoidal, and rotary), tokenization schemes (character-level, word-level, and byte pair encoding), and model size (hyperparameter search over number of heads, layers, and context size) on validation model perplexity. We find that rotary encoding, character-level tokenization, combined with a model architecture of 2 heads, 16 layers, and 256 context length gives the lowest validation perplexity on the Shakespeare dataset.
img: assets/img/transformer_ablation.png
importance: 7
category: work
related_publications: 
---

<div class="caption">
    <body>
    <center>
        <h6 align="left">Transformer Positional Encoding & Tokenization Study</h6>
        <iframe src="../Transformer_Project.pdf" 
                width="800"
                height="500">
        </iframe>
    </center>
</body>
</div>

