Image colorization presents a captivating challenge
within the realm of computer vision, entailing the transformation
of an image from a source domain to a target domain with the
goal of closely mimicking its natural color palette. In the pursuit
of colorization, the primary objective is to generate a faithful
color image that effectively serves the user’s intended purpose,
even if it deviates from the ground truth colors. Initially, we start
by replicating the methodology originally introduced by Isola et
al, which led to pix2pix framework. They have offered GANs in
a conditional setting as a general-purpose solution to image-toimage
translations. To enhance our results, we first experimented
with ResNet and retrained the network. Subsequently, we implemented
WGAN-clipping and WGAN-PG to enhance the stability
of the learning model. Additionally, we applied CycleGAN to
improve the speed of computational processing. Subsequently,
we evaluated these three image colorization models using PSNR
and SSIM metrics. Our contribution seeks to advance the image
recolorization task by incorporating training enhancements that
significantly reduce the requisite dataset size, thereby enhancing
both speed and the logical coherence of colorization outcomes.
