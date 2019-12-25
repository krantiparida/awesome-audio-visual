# Awesome Audio-Visual: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of different papers in the broad area of audio-visual, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

## Contents
 - [Audio-Visual Localization](#Audio-Visual-Localization)
 - [Audio-Visual Separation](#Audio-Visual-Separation)
 - [Audio-Visual Representaion](#Audio-Visual-Representation)
 - [Cross-Modal Retrieval](#Cross-Modal-Retrieval)
 - [Audio-Visual Action Recognition](#Audio-Visual-Action-Recognition)
 - [Audio-Visual Faces/Speech](#Audio-Visual-Faces/Speech)
 - [Cross-modal Generation (Audio-Video / Video-Audio)](#Cross-modal-Generation-(Audio-Video-/-Video-Audio))
 - [Multi-modal Generation](#Multi-modal-Generation)
 - [Multi-modal Architectures](#Multi-modal-Architectures)
 - [Uncategorized Papers](#Uncategorized-Papers)
#### Audio-Visual Localization
* [Dual Attention Matching for Audio-Visual Event Localization](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wu_Dual_Attention_Matching_for_Audio-Visual_Event_Localization_ICCV_2019_paper.pdf) - Wu, Y., Zhu, L., Yan, Y., & Yang, Y. (ICCV 2019)
* [Weakly Supervised Representation Learning for Unsynchronized Audio-Visual Events](https://arxiv.org/pdf/1804.07345.pdf) - Parekh, S., Essid, S., Ozerov, A., Duong, N. Q., Pérez, P., & Richard, G. (arxiv, 2018) [CPVRW2018](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Parekh_Weakly_Supervised_Representation_CVPR_2018_paper.pdf)
* [Learning to Localize Sound Source in Visual Scenes](http://openaccess.thecvf.com/content_cvpr_2018/papers/Senocak_Learning_to_Localize_CVPR_2018_paper.pdf) - Senocak, A., Oh, T. H., Kim, J., Yang, M. H., & Kweon, I. S. (CVPR 2018)
* [Objects that Sound](https://arxiv.org/pdf/1712.06651.pdf) - Arandjelovic, R., & Zisserman, A. (ECCV 2018) 
* [Audio-Visual Event Localization in Unconstrained Videos](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yapeng_Tian_Audio-Visual_Event_Localization_ECCV_2018_paper.pdf) - Tian, Y., Shi, J., Li, B., Duan, Z., & Xu, C. (ECCV 2018) [[project page]](https://sites.google.com/view/audiovisualresearch) [[code]](https://github.com/YapengTian/AVE-ECCV18)

#### Audio-Visual Separation
* [Recursive Visual Sound Separation Using Minus-Plus Net](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Recursive_Visual_Sound_Separation_Using_Minus-Plus_Net_ICCV_2019_paper.pdf) - Xudong Xu, Bo Dai, Dahua Lin (ICCV 2019)
* [Co-Separating Sounds of Visual Objects](https://arxiv.org/pdf/1904.07750.pdf) - Gao, R. & Grauman, K. (ICCV 2019) [[project page]](http://vision.cs.utexas.edu/projects/coseparation/)
* [The sound of Motions](https://arxiv.org/pdf/1904.05979.pdf) - Zhao, H., Gan, C., Ma, W. & Torralba, A. (ICCV 2019)
* [Learning to Separate Object Sounds by Watching Unlabeled Video](http://vision.cs.utexas.edu/projects/separating_object_sounds/sound-sep-eccv2018.pdf) - Gao, R., Feris, R., & Grauman, K. (ECCV 2018 (Oral)) [[project page]](http://vision.cs.utexas.edu/projects/separating_object_sounds/) [[code]](https://github.com/rhgao/Deep-MIML-Network) [[dataset]](http://vision.cs.utexas.edu/projects/separating_object_sounds/#data)
* [The Sound of Pixels](https://arxiv.org/pdf/1804.03160.pdf) - Zhao, H., Gan, C., Rouditchenko, A., Vondrick, C., McDermott, J., & Torralba, A. (ECCV 2018) [[project page]](http://sound-of-pixels.csail.mit.edu/)[[code]](https://github.com/hangzhaomit/Sound-of-Pixels) [[dataset]](https://github.com/roudimit/MUSIC_dataset)
#### Audio-Visual Representation
* [Deep Multimodal Clustering for Unsupervised Audiovisual Learning](https://arxiv.org/pdf/1807.03094.pdf) - (Hu, D., Nie, F., & Li, X. (CVPR 2019))
* [Cooperative learning of audio and video models from self-supervised synchronization](http://papers.nips.cc/paper/8002-cooperative-learning-of-audio-and-video-models-from-self-supervised-synchronization.pdf) - (Korbar, B., Tran, D., & Torresani, L. (NeurIPS 2108)) [[project page]](http://vlg.cs.dartmouth.edu/projects/avts/)[[trained model 1]](http://vlg.cs.dartmouth.edu/projects/avts/model_mc3_as.pt)[[trained model 2]](http://vlg.cs.dartmouth.edu/projects/avts/model_mc2_as.pt)
* [Multimodal Attention for Fusion of Audio and Spatiotemporal Features for Video Description](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Hori_Multimodal_Attention_for_CVPR_2018_paper.pdf) - Hori, C., Hori, T., Wichern, G., Wang, J., Lee, T. Y., Cherian, A., & Marks, T. K. (CVPRW 2018)
* [Audio-Visual Scene Analysis with Self-Supervised Multisensory Features](https://arxiv.org/pdf/1804.03641.pdf) - Owens, A., & Efros, A. A. (ECCV 2018 (Oral)) [[project page]](http://andrewowens.com/multisensory/) [[code]](https://github.com/andrewowens/multisensory)
* [Look, listen and learn](https://arxiv.org/pdf/1705.08168.pdf) - Arandjelovic, R., & Zisserman, A. (ICCV 2017) [[Keras-code]](https://github.com/Kajiyu/LLLNet)
* [Ambient Sound Provides Supervision for Visual Learning](https://arxiv.org/pdf/1608.07017.pdf) - Owens, A., Wu, J., McDermott, J. H., Freeman, W. T., & Torralba, A. (ECCV 2016(Oral)) [[journal version]](https://arxiv.org/pdf/1712.07271.pdf) [[project page]](http://andrewowens.com/ambient/index.html) 
* [Soundnet: Learning sound representations from unlabeled video](http://www.cs.columbia.edu/~vondrick/soundnet.pdf) -  Aytar, Y., Vondrick, C., & Torralba, A. (NIPS 2016) [[project page]](http://projects.csail.mit.edu/soundnet/) [[code]](https://github.com/cvondrick/soundnet)
* [See, hear, and read: Deep aligned representations](https://people.csail.mit.edu/yusuf/publications/2017/Aytar17/aytar17.pdf) - Aytar, Y., Vondrick, C., & Torralba, A. (arxiv 2017) [[project page]](https://people.csail.mit.edu/yusuf/see-hear-read/)

#### Cross-Modal Retrieval
* [Learning Cross-modal Embeddings for Cooking Recipes and Food Images](http://pic2recipe.csail.mit.edu/im2recipe.pdf) -  Salvador, A., Hynes, N., Aytar, Y., Marin, J., Ofli, F., Weber, I., & Torralba, A. (CVPR 2017)
* [Cross-Modal Embeddings for Video and Audio Retrieval](https://arxiv.org/pdf/1801.02200.pdf) -Surís, D., Duarte, A., Salvador, A., Torres, J., & Giró-i-Nieto, X. (ECCVW, 2018)

#### Audio-Visual Action Recognition
* [Listen to Look: Action Recognition by Previewing Audio](https://arxiv.org/pdf/1912.04487.pdf) -  Ruohan Gao, Tae-Hyun Oh, Kristen Grauman, Lorenzo Torresani (ArXiv 2019) [[project page]](http://vision.cs.utexas.edu/projects/listen_to_look/)
* [Uncertainty-aware Audiovisual Activity Recognition using Deep Bayesian Variational Inference](http://openaccess.thecvf.com/content_ICCV_2019/papers/Subedar_Uncertainty-Aware_Audiovisual_Activity_Recognition_Using_Deep_Bayesian_Variational_Inference_ICCV_2019_paper.pdf) - Subedar, M., Krishnan, R., Meyer, P. L., Tickoo, O., & Huang, J. (ICCV 2019)
* [Seeing and Hearing Egocentric Actions: How Much Can We Learn?](http://openaccess.thecvf.com/content_ICCVW_2019/papers/EPIC/Cartas_Seeing_and_Hearing_Egocentric_Actions_How_Much_Can_We_Learn_ICCVW_2019_paper.pdf) - Cartas, A., Luque, J., Radeva, P., Segura, C., & Dimiccoli, M. (ICCVW 2019)
* [How Much Does Audio Matter to Recognize Egocentric Object Interactions?](https://arxiv.org/pdf/1906.00634.pdf) - Cartas, A., Luque, J., Radeva, P., Segura, C., & Dimiccoli, M. (EPIC CVPRW 2019)

#### Audio-Visual Faces/Speech
* [Reconstructing faces from voices](https://arxiv.org/pdf/1905.10604.pdf) - Yandong Wen, Rita Singh, Bhiksha Raj (NIPS 2019)[[project page]](https://github.com/cmu-mlsp/reconstructing_faces_from_voices)
* [Learning Individual Styles of Conversational Gesture](https://arxiv.org/pdf/1906.04160.pdf) - Ginosar, S., Bar, A., Kohavi, G., Chan, C., Owens, A., & Malik, J. (CVPR 2019) [[project page]](http://people.eecs.berkeley.edu/~shiry/projects/speech2gesture/) [[dataset]](https://drive.google.com/drive/folders/1qvvnfGwas8DUBrwD4DoBnvj8anjSLldZ)
* [Hierarchical Cross-Modal Talking Face Generation with Dynamic Pixel-Wise Loss](https://www.cs.rochester.edu/u/lchen63/cvpr2019.pdf) - Chen, L., Maddox, R. K., Duan, Z., & Xu, C. (CVPR 2019)[[project page]](https://github.com/lelechen63/ATVGnet)
* [Speech2Face: Learning the Face Behind a Voice](https://arxiv.org/pdf/1905.09773.pdf) - Oh, T. H., Dekel, T., Kim, C., Mosseri, I., Freeman, W. T., Rubinstein, M., & Matusik, W. (CVPR 2019)[[project page]](https://speech2face.github.io/)
* [Talking Face Generation by Adversarially Disentangled Audio-Visual Representation](https://arxiv.org/pdf/1807.07860.pdf) - Hang Zhou, Yu Liu, Ziwei Liu, Ping Luo, Xiaogang Wang (AAAI 2019) [[project page]](https://liuziwei7.github.io/projects/TalkingFace) [[code]](https://github.com/Hangz-nju-cuhk/Talking-Face-Generation-DAVS)
* [Disjoint mapping network for cross-modal matching of voices and faces](https://openreview.net/pdf?id=B1exrnCcF7) - Wen, Y., Ismail, M. A., Liu, W., Raj, B., & Singh, R. (ICLR 2019)[[project page]](https://github.com/ydwen/DIMNet)
* [X2Face: A network for controlling face generation using images, audio, and pose codes](http://openaccess.thecvf.com/content_ECCV_2018/papers/Olivia_Wiles_X2Face_A_network_ECCV_2018_paper.pdf) - Wiles, O., Sophia Koepke, A., & Zisserman, A. (ECCV 2018)[[project page]](http://www.robots.ox.ac.uk/~vgg/research/unsup_learn_watch_faces/x2face.html)[[code]](https://github.com/oawiles/X2Face)
* [Learnable PINs: Cross-Modal Embeddings for Person Identity](https://arxiv.org/pdf/1805.00833.pdf) - Nagrani, A., Albanie, S., & Zisserman, A. (ECCV 2018)[[project page]](http://www.robots.ox.ac.uk/~vgg/research/LearnablePins/)
* [Seeing voices and hearing faces: Cross-modal biometric matching](http://www.robots.ox.ac.uk/~vgg/publications/2018/Nagrani18a/nagrani18a.pdf) - Nagrani, A., Albanie, S., & Zisserman, A. (CVPR 2018) [[project page]](http://www.robots.ox.ac.uk/~vgg/research/CMBiometrics/)[[code]](https://github.com/a-nagrani/SVHF-Net)(trained moodel only)
* [VoxCeleb2: Deep Speaker Recognition](https://arxiv.org/pdf/1806.05622.pdf) - Nagrani, A., Chung, J. S., & Zisserman, A. (Interspeech 2018) [[dataset]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)
* [You said that?](http://www.robots.ox.ac.uk/~vgg/publications/2017/Chung17b/chung17b.pdf) - Son Chung, J., Jamaludin, A., & Zisserman, A. (BMVC 2017) [[project page]](http://www.robots.ox.ac.uk/~vgg/software/yousaidthat/) [[code]](https://github.com/joonson/yousaidthat)(trained model, evaluation code)
* [VoxCeleb: a large-scale speaker identification dataset](http://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/nagrani17.pdf) - Nagrani, A., Chung, J. S., & Zisserman, A. (Interspeech 2017) [[project page]](http://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/)[[code]](https://github.com/a-nagrani/VGGVox) [[dataset]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)

#### Cross-modal Generation (Audio-Video / Video-Audio)
* [Unpaired Image-to-Speech Synthesis with Multimodal Information Bottleneck](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Unpaired_Image-to-Speech_Synthesis_With_Multimodal_Information_Bottleneck_ICCV_2019_paper.pdf) - (Shuang Ma, Daniel McDuff, Yale Song (ICCV 2019)) [[code]](https://github.com/yunyikristy/skipNet)
* [Listen to the Image](https://arxiv.org/pdf/1904.09115.pdf) - (Hu, D., Wang, D., Li, X., Nie, F., & Wang, Q. (CVPR 2019))
* [Visual to Sound: Generating Natural Sound for Videos in the Wild](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Visual_to_Sound_CVPR_2018_paper.pdf) - (Zhou, Y., Wang, Z., Fang, C., Bui, T., & Berg, T. L. (CVPR 2018))[[project page]](http://bvision11.cs.unc.edu/bigpen/yipin/visual2sound_webpage/visual2sound.html)
* [Image generation associated with music data](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Qiu_Image_Generation_Associated_CVPR_2018_paper.pdf) - Qiu, Y., & Kataoka, H. (CVPRW 2018)

#### Multi-modal Generation
* [Multimodal generative models for scalable weakly-supervised learning](https://papers.nips.cc/paper/7801-multimodal-generative-models-for-scalable-weakly-supervised-learning.pdf) - Wu, M., & Goodman, N. (NeurIPS 2018)

#### Multi-modal Architectures
* [What Makes Training Multi-Modal Networks Hard?](https://arxiv.org/pdf/1905.12681.pdf) - Wang, W., Tran, D., & Feiszli, M. (ArXiv 2019) 
* [MFAS: Multimodal Fusion Architecture Search](http://openaccess.thecvf.com/content_CVPR_2019/papers/Perez-Rua_MFAS_Multimodal_Fusion_Architecture_Search_CVPR_2019_paper.pdf) - Pérez-Rúa, J. M., Vielzeuf, V., Pateux, S., Baccouche, M., & Jurie, F. (CVPR 2019)

#### Uncategorized Papers
* [Self-supervised Moving Vehicle Tracking with Stereo Sound](http://openaccess.thecvf.com/content_ICCV_2019/papers/Gan_Self-Supervised_Moving_Vehicle_Tracking_With_Stereo_Sound_ICCV_2019_paper.pdf) - Gan, C., Zhao, H., Chen, P., Cox, D., & Torralba, A. (ICCV 2019)
* [Vision-Infused Deep Audio Inpainting](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Vision-Infused_Deep_Audio_Inpainting_ICCV_2019_paper.pdf) - Zhou, H., Liu, Z., Xu, X., Luo, P., & Wang, X. (ICCV 2019) [[project page]](https://hangz-nju-cuhk.github.io/projects/AudioInpainting) [[code]](https://github.com/Hangz-nju-cuhk/Vision-Infused-Audio-Inpainter-VIAI)
* [ISNN: Impact Sound Neural Network for Audio-Visual Object Classification](http://openaccess.thecvf.com/content_ECCV_2018/papers/Auston_Sterling_ISNN_-_Impact_ECCV_2018_paper.pdf) - Sterling, A., Wilson, J., Lowe, S., & Lin, M. C. (ECCV 2018) [[project page]](http://gamma.cs.unc.edu/ISNN/) [[dataset1]](https://drive.google.com/drive/folders/1lVYYMTOLItozaU-vAa0OoXQr_4VfmqVg?usp=sharing)[[dataset2]](https://drive.google.com/drive/folders/1p0HAlrsoydYFuWginPuhiDQjncAvSQon?usp=sharing) [[model]](http://gamma.cs.unc.edu/ISNN/ModelNet_URLs_WAV_PLY.pdf)
* [Audio to Body Dynamics](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shlizerman_Audio_to_Body_CVPR_2018_paper.pdf) - Shlizerman, E., Dery, L., Schoen, H., & Kemelmacher-Shlizerman, I. (CVPR 2018) [[project page]](https://arviolin.github.io/AudioBodyDynamics/)[[code]](https://github.com/facebookresearch/Audio2BodyDynamics)
* [A Multimodal Approach to Mapping Soundscapes](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Salem_A_Multimodal_Approach_CVPR_2018_paper.pdf) - Salem, T., Zhai, M., Workman, S., & Jacobs, N. (CVPRW 2018) [[project page]](http://cs.uky.edu/~salem/audio-mapping/)
* [Shape and material from sound](https://papers.nips.cc/paper/6727-shape-and-material-from-sound.pdf) - Zhang, Z., Li, Q., Huang, Z., Wu, J., Tenenbaum, J., & Freeman, B. (NeurIPS 2017)

## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Kranti Kumar Parida](https://krantiparida.github.io/) has waived all copyright and related or neighboring rights to this work.

## Contributing
Please feel free to send me [pull requests]() or email (kranti@cse.iitk.ac.in) to add links.