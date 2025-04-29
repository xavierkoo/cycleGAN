# CycleGAN for Image-to-Image Translation: Implementation, Optimization & Novel Applications

<p>
                    Image-to-image translation using Generative Adversarial Networks (GANs) has
                    witnessed rapid advancements, with CycleGAN emerging as a key framework for
                    unsupervised domain transfer. This project explores and enhances CycleGAN through
                    two distinct tasks: (1) photorealistic face-to-cartoon translation and (2) young-to-old facial
                    age progression. To address limitations in vanilla CycleGAN, such as poor structural
                    preservation, training instability, and lack of global context, architectural
                    innovations were introduced, including dual self-attention modules, perceptual VGG-based loss functions,
                    edge-aware enhancements, and spectral normalization in discriminators. Additionally,
                    training strategies like warm-up cosine annealing, AMP for mixed-precision training,
                    and gradient clipping for improved stability were adopted. 
                </p>
                <br />
                <p>
                    Quantitative and qualitative evaluations
                    demonstrate significant improvements across both tasks. For Task 1, the enhanced model
                    achieved lower GMS scores—indicating higher visual realism—compared to the vanilla
                    CycleGAN, particularly in the Real-to-Cartoon direction. For Task 2, ablation studies
                    show that the integration of VGG loss and self-attention yields the most visually convincing
                    and age-accurate transformations, with an average age gap reduction from 20.73 to 7.54.
                    Experiments validate that these enhancements not only improve visual fidelity but also
                    align closely with semantic expectations of aging and style translation, pushing the
                    boundaries of what unsupervised translation frameworks can achieve in facial domains.
                </p>
