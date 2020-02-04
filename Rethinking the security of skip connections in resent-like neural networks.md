# Motivation: 
1. A skip connection builds a short-cut from a shallow layer to a deep layer by connecting the input of a residual enable training deeper networks. It can help preserve low-level features and avoid performance degradation when adding more layers.
2. Black box attack often suffers from low transferability in black-box setting.
3. Gradients from the skip connections are more vulnerable and also expose more transferable information.

# Skip Gradient Method:
They introduce a decay parameter into the decomposed gradient from the residual modules.
