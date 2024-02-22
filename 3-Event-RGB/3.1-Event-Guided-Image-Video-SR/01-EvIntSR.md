# EvIntSR-Net: Event Guided Multiple Latent Frames Reconstruction and Super-resolution

ICCV, 2021

The methodology of this article was summarized earlier. Here we only summarize the ablation study. 
In summary, the method of this paper has two modules, divided into three parts. They are LFR-Net, MIF-Net respectively. Where MIF-Net includes DCB and Feedback block.

Firstly, the latent frames can be computed directly from the APS frame and event stacks. To prove the necessity of LFR-Net, they remove LFR-Net and use the latent frames reconstructed. In addition, they remove the deformable convolution block (W/o DC align) and feedback block (W/o FB block) to verify the significance of latent frames alignment and recurrent manner in MIF-Net, respectively. 