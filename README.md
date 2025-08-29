# Offensive-Memes-Detection
Abstract—Aggressive meme is a very potent tool for cyberstalker to bully people online. To ensure a safe online place,
we need a robust mechanism to detect aggressive memes. However, working with a low-resource language like Bangla
presents distinctive challenges. This paper presents BlipART (Blip And banglabeRT), a hybrid multimodal approach that
combines pretrained models to detect aggressive memes in Bengali, where the Bootstrapping Language-Image Pretraining
(BLIP) and BanglaBERT combination achieves the highest accuracy, which is 99.59%. Our approach integrates enhanced
image preprocessing and employs strategic image augmentation to improve model generalization. This research also develops
a cross-validation approach to demonstrate the robustness of the model. The outcome of this study is interpreted through
XAI, building transparency by showing how the model makes decisions. The proposed system not only addresses linguistic and
cultural nuances in meme-based cyberbullying but also sets a new benchmark for aggression detection, which helps mitigate
online harassment. 
Index Terms—Cyberbullying, Multimodal analysis, Aggressive
Memes, BLIP, BanglaBERT

The summary of the main contributions of our work is given
below:
• Achieved very high accuracy of 99.59% on the memes
dataset, which is a significant improvement on prior art,
which was 74.1% on the same dataset [13].
• Applied CLAHE filter, which enhances the contrast of
the image, and image augmentation, which improves the
performance and generalization of deep learning models.
• We have used several multimodal vision-language models combination. Among them BLIP and BanglaBERT
combination performs best.
• We have used 10-fold cross-validation for the best model
to prove the robustness of our approach.
• The output of this research is interpreted by LIME [14]
Explainable Artificial Intelligence (XAI)
