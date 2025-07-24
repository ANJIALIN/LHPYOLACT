# Lightweight High-Precision Monitoring of Damage Locations in Dunhuang Murals Based on Improved YOLACT

## Abstract

As an important cultural heritage of China and a world treasure, the Dunhuang murals have undergone thousands of years of weathering, oxidation, and human interference, resulting in extensive damage such as cracks, peeling, and fading on their surfaces. Additionally, due to their complex colour palette, it is challenging to quickly identify damaged areas, leading to a situation where the rate of damage to the Dunhuang murals far exceeds the rate of restoration. To achieve efficient and precise monitoring of damage to Dunhuang murals and support cultural heritage preservation efforts, this paper proposes an improved lightweight, high-precision method for monitoring the location of damage to Dunhuang murals based on YOLACT. First, addressing the limitation of traditional YOLACT models in extracting fine-grained texture features, a residual self-attention mechanism capable of extracting global features is introduced to enhance the model's feature extraction capability (mAP50: 79.2064 $\%$). Subsequently, by introducing a depth-separable convolutional architecture, the goal of lightweight design is achieved while maintaining high accuracy (parameter count: 715.12 k, floating-point operations: 70.219 M). Finally, to validate the model's effectiveness, this paper conducted validation on a public dataset. Experimental results show that, compared to three mainstream models, the proposed method achieves the highest mAP50 and the smallest parameter count and floating-point operations.

## Dataset

The dataset used in this article is a public dataset. The original link is as follows: https://www.nature.com/articles/s41597-024-03785-0

## Code

The code mentioned in this article will be uploaded after the paper is accepted. If you are interested in the effect of this article, you can look at the currently uploaded folder, which contains the trained model weights, test samples, and deployment links. At the same time, after uploading the code, we will open source our deployment method.

