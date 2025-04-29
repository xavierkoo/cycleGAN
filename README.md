# cycleGAN

Image-to-image translation using Generative Adversarial Networks (GANs) has
witnessed rapid advancements, with CycleGAN emerging as a key framework for
unsupervised domain transfer. In this project, we explore and enhance CycleGAN through
two distinct tasks: (1) photorealistic face-to-cartoon translation and (2) young-to-old facial
age progression. To address limitations in vanilla CycleGAN, such as poor structural
preservation, training instability, and lack of global context, we introduce architectural
innovations, including dual self-attention modules, perceptual VGG-based loss functions,
edge-aware enhancements, and spectral normalization in discriminators. Additionally, we
adopt training strategies like warm-up cosine annealing, AMP for mixed-precision training,
and gradient clipping for improved stability. Quantitative and qualitative evaluations
demonstrate significant improvements across both tasks. For Task 1, our enhanced model
achieved lower GMS scores—indicating higher visual realism—compared to the vanilla
CycleGAN, particularly in the Real-to-Cartoon direction. For Task 2, our ablation studies
show that the integration of VGG loss and self-attention yields the most visually convincing
and age-accurate transformations, with an average age gap reduction from 20.73 to 7.54.
Our experiments validate that these enhancements not only improve visual fidelity but also
align closely with semantic expectations of aging and style translation, pushing 
