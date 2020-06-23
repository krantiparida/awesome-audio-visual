# Awesome Audio-Visual: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of papers and datsets for various audio-visual tasks, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

## Contents
 - [Audio-Visual Localization](#Audio-Visual-Localization)
 - [Audio-Visual Separation](#Audio-Visual-Separation)
 - [Audio-Visual Representaion](#Audio-Visual-Representation)
 - [Audio-Visual Action Recognition](#Audio-Visual-Action-Recognition)
 - [Audio-Visual Spatial/Depth](#Audio-Visual-Spatialdepth)
 - [Audio-Visual Faces/Speech](#Audio-Visual-Facesspeech)
 - [Cross-modal Generation (Audio-Video / Video-Audio)](#Cross-modal-Generation-(Audio-Video--Video-Audio))
 - [Multi-modal Architectures](#Multi-modal-Architectures)
 - [Uncategorized Papers](#Uncategorized-Papers)

#### Audio-Visual Localization
* [Learning Differentiable Sparse and Low Rank Networks for Audio-Visual Object Localization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9054280) - Pu, J., Panagakis, Y., & Pantic, M. (ICASSP 2020)
* [What Makes the Sound?: A Dual-Modality Interacting Network for Audio-Visual Event Localization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9053895) - Ramaswamy, J. (ICASSP 2020)
* [Self-supervised learning for audio-visual speaker diarization](https://arxiv.org/pdf/2002.05314.pdf) - Ding, Y., Xu, Y., Zhang, S. X., Cong, Y., & Wang, L. (ICASSP 2020)
* [See the Sound, Hear the Pixels](http://openaccess.thecvf.com/content_WACV_2020/papers/Ramaswamy_See_the_Sound_Hear_the_Pixels_WACV_2020_paper.pdf) - Ramaswamy, J., & Das, S. (WACV 2020)
* [Dual Attention Matching for Audio-Visual Event Localization](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wu_Dual_Attention_Matching_for_Audio-Visual_Event_Localization_ICCV_2019_paper.pdf) - Wu, Y., Zhu, L., Yan, Y., & Yang, Y. (ICCV 2019)
* [Weakly Supervised Representation Learning for Unsynchronized Audio-Visual Events](https://arxiv.org/pdf/1804.07345.pdf) - Parekh, S., Essid, S., Ozerov, A., Duong, N. Q., Pérez, P., & Richard, G. (arxiv, 2018) [CPVRW2018](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Parekh_Weakly_Supervised_Representation_CVPR_2018_paper.pdf)
* [Learning to Localize Sound Source in Visual Scenes](http://openaccess.thecvf.com/content_cvpr_2018/papers/Senocak_Learning_to_Localize_CVPR_2018_paper.pdf) - Senocak, A., Oh, T. H., Kim, J., Yang, M. H., & Kweon, I. S. (CVPR 2018)
* [Objects that Sound](https://arxiv.org/pdf/1712.06651.pdf) - Arandjelovic, R., & Zisserman, A. (ECCV 2018) 
* [Audio-Visual Event Localization in Unconstrained Videos](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yapeng_Tian_Audio-Visual_Event_Localization_ECCV_2018_paper.pdf) - Tian, Y., Shi, J., Li, B., Duan, Z., & Xu, C. (ECCV 2018) [[project page]](https://sites.google.com/view/audiovisualresearch) [[code]](https://github.com/YapengTian/AVE-ECCV18)
* [Audio-visual object localization and separation using low-rank and sparsity](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7952687) - Pu, J., Panagakis, Y., Petridis, S., & Pantic, M. (ICASSP 2017)
#### Audio-Visual Separation
* [Visually Guided Sound Source Separation using Cascaded Opponent Filter Network. arXiv](https://arxiv.org/pdf/2006.03028.pdf) - Zhu, L., & Rahtu, E. (arXiv 2020) [[project page]](https://ly-zhu.github.io/cof-net)
* [Music Gesture for Visual Sound Separation](https://arxiv.org/pdf/2004.09476.pdf) - Gan, C., Huang, D., Zhao, H., Tenenbaum, J. B., & Torralba, A. (CVPR 2020) [[project page]](http://music-gesture.csail.mit.edu/) [[code]](http://music-gesture.csail.mit.edu/#code)
* [Recursive Visual Sound Separation Using Minus-Plus Net](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Recursive_Visual_Sound_Separation_Using_Minus-Plus_Net_ICCV_2019_paper.pdf) - Xudong Xu, Bo Dai, Dahua Lin (ICCV 2019)
* [Co-Separating Sounds of Visual Objects](https://arxiv.org/pdf/1904.07750.pdf) - Gao, R. & Grauman, K. (ICCV 2019) [[project page]](http://vision.cs.utexas.edu/projects/coseparation/)
* [The sound of Motions](https://arxiv.org/pdf/1904.05979.pdf) - Zhao, H., Gan, C., Ma, W. & Torralba, A. (ICCV 2019)
* [Learning to Separate Object Sounds by Watching Unlabeled Video](http://vision.cs.utexas.edu/projects/separating_object_sounds/sound-sep-eccv2018.pdf) - Gao, R., Feris, R., & Grauman, K. (ECCV 2018 (Oral)) [[project page]](http://vision.cs.utexas.edu/projects/separating_object_sounds/) [[code]](https://github.com/rhgao/Deep-MIML-Network) [[dataset]](http://vision.cs.utexas.edu/projects/separating_object_sounds/#data)
* [The Sound of Pixels](https://arxiv.org/pdf/1804.03160.pdf) - Zhao, H., Gan, C., Rouditchenko, A., Vondrick, C., McDermott, J., & Torralba, A. (ECCV 2018) [[project page]](http://sound-of-pixels.csail.mit.edu/) [[code]](https://github.com/hangzhaomit/Sound-of-Pixels) [[dataset]](https://github.com/roudimit/MUSIC_dataset)

#### Audio-Visual Representation/Classification
* [Vggsound: A Large-Scale Audio-Visual Dataset](https://www.robots.ox.ac.uk/~vgg/publications/2020/Chen20/chen20.pdf) - Chen, H., Xie, W., Vedaldi, A., & Zisserman, A. (ICASSP 2020) [[project page/dataset]](http://www.robots.ox.ac.uk/~vgg/data/vggsound/) [[code]](https://github.com/hche11/VGGSound)
* [Large Scale Audiovisual Learning of Sounds with Weakly Labeled Data](https://arxiv.org/pdf/2006.01595.pdf) - Fayek, H. M., & Kumar, A. (IJCAI 2020)
* [Multi-modal Self-Supervision from Generalized Data Transformations](https://arxiv.org/pdf/2003.04298.pdf) - Patrick, M., Asano, Y. M., Fong, R., Henriques, J. F., Zweig, G., & Vedaldi, A. (arXiv 2020)
* [Curriculum Audiovisual Learning](https://arxiv.org/pdf/2001.09414.pdf) - Hu, D., Wang, Z., Xiong, H., Wang, D., Nie, F., & Dou, D. (arXiv 2020)
* [Audio-visual model distillation using acoustic images]() - Perez, A., Sanguineti, V., Morerio, P., & Murino, V. (WACV 2020) [[code]](https://github.com/afperezm/acoustic-images-distillation) [[dataset]](https://pavis.iit.it/datasets/audio-visually-indicated-actions-dataset)
* [Coordinated Joint Multimodal Embeddings for Generalized Audio-Visual Zero-shot Classification and Retrieval of Videos](http://openaccess.thecvf.com/content_WACV_2020/papers/Parida_Coordinated_Joint_Multimodal_Embeddings_for_Generalized_Audio-Visual_Zero-shot_Classification_and_WACV_2020_paper.pdf) - Parida, K., Matiyali, N., Guha, T., & Sharma, G. (WACV 2020) [[project page]](https://www.cse.iitk.ac.in/users/kranti/avzsl.html)[[Dataset]](https://github.com/krantiparida/AudioSetZSL)
* [Self-Supervised Learning by Cross-Modal Audio-Video Clustering](https://arxiv.org/pdf/1911.12667.pdf) - Alwassel, H., Mahajan, D., Torresani, L., Ghanem, B., & Tran, D. (arXiv 2019)
* [Look, listen, and learn more: Design choices for deep audio embeddings](http://www.justinsalamon.com/uploads/4/3/9/4/4394963/cramer_looklistenlearnmore_icassp_2019.pdf) - Cramer, J., Wu, H. H., Salamon, J., & Bello, J. P. (ICASSP 2019) [[code]](https://github.com/marl/openl3) [[L3-embedding]](https://github.com/marl/l3embedding)
* [Self-supervised audio-visual co-segmentation](https://arxiv.org/pdf/1904.09013.pdf) - Rouditchenko, A., Zhao, H., Gan, C., McDermott, J., & Torralba, A. (ICASSP 2019)
* [Deep Multimodal Clustering for Unsupervised Audiovisual Learning](https://arxiv.org/pdf/1807.03094.pdf) - (Hu, D., Nie, F., & Li, X. (CVPR 2019))
* [Cooperative learning of audio and video models from self-supervised synchronization](http://papers.nips.cc/paper/8002-cooperative-learning-of-audio-and-video-models-from-self-supervised-synchronization.pdf) - (Korbar, B., Tran, D., & Torresani, L. (NeurIPS 2108)) [[project page]](http://vlg.cs.dartmouth.edu/projects/avts/)[[trained model 1]](http://vlg.cs.dartmouth.edu/projects/avts/model_mc3_as.pt)[[trained model 2]](http://vlg.cs.dartmouth.edu/projects/avts/model_mc2_as.pt)
* [Multimodal Attention for Fusion of Audio and Spatiotemporal Features for Video Description](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Hori_Multimodal_Attention_for_CVPR_2018_paper.pdf) - Hori, C., Hori, T., Wichern, G., Wang, J., Lee, T. Y., Cherian, A., & Marks, T. K. (CVPRW 2018)
* [Audio-Visual Scene Analysis with Self-Supervised Multisensory Features](https://arxiv.org/pdf/1804.03641.pdf) - Owens, A., & Efros, A. A. (ECCV 2018 (Oral)) [[project page]](http://andrewowens.com/multisensory/) [[code]](https://github.com/andrewowens/multisensory)
* [Look, listen and learn](https://arxiv.org/pdf/1705.08168.pdf) - Arandjelovic, R., & Zisserman, A. (ICCV 2017) [[Keras-code]](https://github.com/Kajiyu/LLLNet)
* [Ambient Sound Provides Supervision for Visual Learning](https://arxiv.org/pdf/1608.07017.pdf) - Owens, A., Wu, J., McDermott, J. H., Freeman, W. T., & Torralba, A. (ECCV 2016(Oral)) [[journal version]](https://arxiv.org/pdf/1712.07271.pdf) [[project page]](http://andrewowens.com/ambient/index.html) 
* [Soundnet: Learning sound representations from unlabeled video](http://www.cs.columbia.edu/~vondrick/soundnet.pdf) -  Aytar, Y., Vondrick, C., & Torralba, A. (NIPS 2016) [[project page]](http://projects.csail.mit.edu/soundnet/) [[code]](https://github.com/cvondrick/soundnet)
* [See, hear, and read: Deep aligned representations](https://people.csail.mit.edu/yusuf/publications/2017/Aytar17/aytar17.pdf) - Aytar, Y., Vondrick, C., & Torralba, A. (arXiv 2017) [[project page]](https://people.csail.mit.edu/yusuf/see-hear-read/)
* [Cross-Modal Embeddings for Video and Audio Retrieval](https://arxiv.org/pdf/1801.02200.pdf) -Surís, D., Duarte, A., Salvador, A., Torres, J., & Giró-i-Nieto, X. (ECCVW, 2018)

#### Audio-Visual Action Recognition
* [Speech2Action: Cross-modal Supervision for Action Recognition](http://www.robots.ox.ac.uk/~vgg/publications/2020/Nagrani20/nagrani20.pdf) - Nagrani, A., Sun, C., Ross, D., Sukthankar, R., Schmid, C., & Zisserman, A. (CVPR 2020) [project page, dataset](https://www.robots.ox.ac.uk/~vgg/research/speech2action/)
* [Listen to Look: Action Recognition by Previewing Audio](https://arxiv.org/pdf/1912.04487.pdf) -  Ruohan Gao, Tae-Hyun Oh, Kristen Grauman, Lorenzo Torresani (CVPR 2020) [[project page]](http://vision.cs.utexas.edu/projects/listen_to_look/)
* [EPIC-Fusion: Audio-Visual Temporal Binding for Egocentric Action Recognition](http://openaccess.thecvf.com/content_ICCV_2019/papers/Kazakos_EPIC-Fusion_Audio-Visual_Temporal_Binding_for_Egocentric_Action_Recognition_ICCV_2019_paper.pdf) - Kazakos, E., Nagrani, A., Zisserman, A., & Damen, D. (ICCV 2019) [[project page]](https://ekazakos.github.io/TBN/) [[code]](https://github.com/ekazakos/temporal-binding-network)
* [Uncertainty-aware Audiovisual Activity Recognition using Deep Bayesian Variational Inference](http://openaccess.thecvf.com/content_ICCV_2019/papers/Subedar_Uncertainty-Aware_Audiovisual_Activity_Recognition_Using_Deep_Bayesian_Variational_Inference_ICCV_2019_paper.pdf) - Subedar, M., Krishnan, R., Meyer, P. L., Tickoo, O., & Huang, J. (ICCV 2019)
* [Seeing and Hearing Egocentric Actions: How Much Can We Learn?](http://openaccess.thecvf.com/content_ICCVW_2019/papers/EPIC/Cartas_Seeing_and_Hearing_Egocentric_Actions_How_Much_Can_We_Learn_ICCVW_2019_paper.pdf) - Cartas, A., Luque, J., Radeva, P., Segura, C., & Dimiccoli, M. (ICCVW 2019)
* [How Much Does Audio Matter to Recognize Egocentric Object Interactions?](https://arxiv.org/pdf/1906.00634.pdf) - Cartas, A., Luque, J., Radeva, P., Segura, C., & Dimiccoli, M. (EPIC CVPRW 2019)

#### Audio-Visual Spatial/Depth
* [VisualEchoes: Spatial Image Representation Learning through Echolocation](https://arxiv.org/pdf/2005.01616.pdf) - Gao, R., Chen, C., Al-Halah, Z., Schissler, C., & Grauman, K. (arXiv 2020)
* [BatVision with GCC-PHAT Features for Better Sound to Vision Predictions](http://sightsound.org/papers/2020/Jesper_Haahr_Christensen_BatVision_with_GCC-PHAT_Features_for_Better_Sound_to_Vision_Predictions.pdf) - Christensen, J. H., Hornauer, S., & Yu, S. (CVPRW 2020)
* [Look, listen, and act: Towards audio-visual embodied navigation](https://arxiv.org/pdf/1912.11684.pdf) - Gan, C., Zhang, Y., Wu, J., Gong, B., & Tenenbaum, J. B. (ICRA 2020) [[project page/dataset]](http://avn.csail.mit.edu/)
* [BatVision: Learning to See 3D Spatial Layout with Two Ears](https://arxiv.org/pdf/1912.07011.pdf) - Christensen, J. H., Hornauer, S., & Yu, S. (ICRA 2020) [[dataset/code]](https://github.com/SaschaHornauer/Batvision)
* [Audio-Visual Embodied Navigation](https://arxiv.org/pdf/1912.11474.pdf) - Chen, C., Jain, U., Schissler, C., Gari, S. V. A., Al-Halah, Z., Ithapu, V. K., Robinson P., Grauman, K. (arXiv 2019) [[project page]](http://vision.cs.utexas.edu/projects/audio_visual_navigation/)
* [Semantic Object Prediction and Spatial Sound Super-Resolution with Binaural Sounds](https://arxiv.org/pdf/2003.04210.pdf) - Vasudevan, A. B., Dai, D., & Van Gool, L. (arXiv 2020) [[project page]](https://www.trace.ethz.ch/publications/2020/sound_perception/index.html)
* [Audio-Visual SfM towards 4D reconstruction under dynamic scenes](http://sightsound.org/papers/2020/Takashi_Konno_Audio-Visual_SfM_towards_4D_reconstruction_under_dynamic_scenes.pdf) -  Konno, A., Nishida K., Itoyama K., Nakadai K. (CVPRW 2020)
* [Telling Left From Right: Learning Spatial Correspondence of Sight and Sound](http://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Telling_Left_From_Right_Learning_Spatial_Correspondence_of_Sight_and_CVPR_2020_paper.pdf) - Yang, K., Russell, B., & Salamon, J. (CVPR 2020) [[project page / dataset]](https://karreny.github.io/telling-left-from-right/)

* [2.5D Visual Sound](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gao_2.5D_Visual_Sound_CVPR_2019_paper.pdf) - Gao, R., & Grauman, K. (CVPR 2019) [[project page]](http://vision.cs.utexas.edu/projects/2.5D_visual_sound/) [[dataset]](https://github.com/facebookresearch/FAIR-Play) [[code]](https://github.com/facebookresearch/2.5D-Visual-Sound)

#### Audio-Visual Faces/Speech
* [Discriminative Multi-modality Speech Recognition](http://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Discriminative_Multi-Modality_Speech_Recognition_CVPR_2020_paper.pdf) - Xu, B., Lu, C., Guo, Y., & Wang, J. (CVPR 2020)
* [Learning Individual Speaking Styles for Accurate Lip to Speech Synthesis](http://openaccess.thecvf.com/content_CVPR_2020/papers/Prajwal_Learning_Individual_Speaking_Styles_for_Accurate_Lip_to_Speech_Synthesis_CVPR_2020_paper.pdf) -  Prajwal, K. R., Mukhopadhyay, R., Namboodiri, V. P., & Jawahar, C. V. (CVPR 2020) [[project page/dataset]](http://cvit.iiit.ac.in/research/projects/cvit-projects/speaking-by-observing-lip-movements#) [[code]](https://github.com/Rudrabha/Lip2Wav)
* [DAVD-Net: Deep Audio-Aided Video Decompression of Talking Heads](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_DAVD-Net_Deep_Audio-Aided_Video_Decompression_of_Talking_Heads_CVPR_2020_paper.pdf) - Zhang, X., Wu, X., Zhai, X., Ben, X., & Tu, C. (CVPR 2020) 
* [Learning to Have an Ear for Face Super-Resolution](http://openaccess.thecvf.com/content_CVPR_2020/papers/Meishvili_Learning_to_Have_an_Ear_for_Face_Super-Resolution_CVPR_2020_paper.pdf) - Meishvili, G., Jenni, S., & Favaro, P. (CVPR 2020) [[project page]](https://gmeishvili.github.io/ear_for_face_super_resolution/index.html) [[code]](https://github.com/gmeishvili/ear_for_face_super_resolution)
* [Visually guided self supervised learning of speech representations](https://arxiv.org/pdf/2001.04316.pdf) - Shukla, A., Vougioukas, K., Ma, P., Petridis, S., & Pantic, M. (ICASSP 2020) 
* [Disentangled Speech Embeddings using Cross-modal Self-supervision](https://arxiv.org/pdf/2002.08742.pdf) - Nagrani, A., Chung, J. S., Albanie, S., & Zisserman, A. (ICASSP 2020)
* [Animating Face using Disentangled Audio Representations](http://openaccess.thecvf.com/content_WACV_2020/papers/Mittal_Animating_Face_using_Disentangled_Audio_Representations_WACV_2020_paper.pdf) - Mittal, G., & Wang, B. (WACV 2020)
* [Reconstructing faces from voices](https://arxiv.org/pdf/1905.10604.pdf) - Yandong Wen, Rita Singh, Bhiksha Raj (NIPS 2019)[[project page]](https://github.com/cmu-mlsp/reconstructing_faces_from_voices)
* [Learning Individual Styles of Conversational Gesture](https://arxiv.org/pdf/1906.04160.pdf) - Ginosar, S., Bar, A., Kohavi, G., Chan, C., Owens, A., & Malik, J. (CVPR 2019) [[project page]](http://people.eecs.berkeley.edu/~shiry/projects/speech2gesture/) [[dataset]](https://drive.google.com/drive/folders/1qvvnfGwas8DUBrwD4DoBnvj8anjSLldZ)
* [Hierarchical Cross-Modal Talking Face Generation with Dynamic Pixel-Wise Loss](https://www.cs.rochester.edu/u/lchen63/cvpr2019.pdf) - Chen, L., Maddox, R. K., Duan, Z., & Xu, C. (CVPR 2019)[[project page]](https://github.com/lelechen63/ATVGnet)
* [Speech2Face: Learning the Face Behind a Voice](https://arxiv.org/pdf/1905.09773.pdf) - Oh, T. H., Dekel, T., Kim, C., Mosseri, I., Freeman, W. T., Rubinstein, M., & Matusik, W. (CVPR 2019)[[project page]](https://speech2face.github.io/)
* [Talking Face Generation by Adversarially Disentangled Audio-Visual Representation](https://arxiv.org/pdf/1807.07860.pdf) - Hang Zhou, Yu Liu, Ziwei Liu, Ping Luo, Xiaogang Wang (AAAI 2019) [[project page]](https://liuziwei7.github.io/projects/TalkingFace) [[code]](https://github.com/Hangz-nju-cuhk/Talking-Face-Generation-DAVS)
* [Disjoint mapping network for cross-modal matching of voices and faces](https://openreview.net/pdf?id=B1exrnCcF7) - Wen, Y., Ismail, M. A., Liu, W., Raj, B., & Singh, R. (ICLR 2019)[[project page]](https://github.com/ydwen/DIMNet)
* [X2Face: A network for controlling face generation using images, audio, and pose codes](http://openaccess.thecvf.com/content_ECCV_2018/papers/Olivia_Wiles_X2Face_A_network_ECCV_2018_paper.pdf) - Wiles, O., Sophia Koepke, A., & Zisserman, A. (ECCV 2018)[[project page]](http://www.robots.ox.ac.uk/~vgg/research/unsup_learn_watch_faces/x2face.html)[[code]](https://github.com/oawiles/X2Face)
* [Learnable PINs: Cross-Modal Embeddings for Person Identity](https://arxiv.org/pdf/1805.00833.pdf) - Nagrani, A., Albanie, S., & Zisserman, A. (ECCV 2018)[[project page]](http://www.robots.ox.ac.uk/~vgg/research/LearnablePins/)
* [Seeing voices and hearing faces: Cross-modal biometric matching](http://www.robots.ox.ac.uk/~vgg/publications/2018/Nagrani18a/nagrani18a.pdf) - Nagrani, A., Albanie, S., & Zisserman, A. (CVPR 2018) [[project page]](http://www.robots.ox.ac.uk/~vgg/research/CMBiometrics/)[[code]](https://github.com/a-nagrani/SVHF-Net)(trained moodel only)
* [Looking to Listen at the Cocktail Party: A Speaker-Independent Audio-Visual Model for Speech Separation](https://arxiv.org/pdf/1804.03619.pdf) - Ephrat, A., Mosseri, I., Lang, O., Dekel, T., Wilson, K., Hassidim, A., Freeman, W.T. and Rubinstein, M., (SIGGRAPH 2018) [[project page]](https://looking-to-listen.github.io/)
* [VoxCeleb2: Deep Speaker Recognition](https://arxiv.org/pdf/1806.05622.pdf) - Nagrani, A., Chung, J. S., & Zisserman, A. (Interspeech 2018) [[dataset]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)
* [You said that?](http://www.robots.ox.ac.uk/~vgg/publications/2017/Chung17b/chung17b.pdf) - Son Chung, J., Jamaludin, A., & Zisserman, A. (BMVC 2017) [[project page]](http://www.robots.ox.ac.uk/~vgg/software/yousaidthat/) [[code]](https://github.com/joonson/yousaidthat)(trained model, evaluation code)
* [VoxCeleb: a large-scale speaker identification dataset](http://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/nagrani17.pdf) - Nagrani, A., Chung, J. S., & Zisserman, A. (Interspeech 2017) [[project page]](http://www.robots.ox.ac.uk/~vgg/publications/2017/Nagrani17/)[[code]](https://github.com/a-nagrani/VGGVox) [[dataset]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)

#### Cross-modal Generation (Audio-Video / Video-Audio)
* [Spectrogram Analysis Via Self-Attention for Realizing Cross-Model Visual-Audio Generation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9052918) - Tan, H., Wu, G., Zhao, P., & Chen, Y. (ICASSP 2020)
* [Unpaired Image-to-Speech Synthesis with Multimodal Information Bottleneck](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Unpaired_Image-to-Speech_Synthesis_With_Multimodal_Information_Bottleneck_ICCV_2019_paper.pdf) - (Shuang Ma, Daniel McDuff, Yale Song (ICCV 2019)) [[code]](https://github.com/yunyikristy/skipNet)
* [Listen to the Image](https://arxiv.org/pdf/1904.09115.pdf) - (Hu, D., Wang, D., Li, X., Nie, F., & Wang, Q. (CVPR 2019))
* [Cascade attention guided residue learning GAN for cross-modal translation](https://arxiv.org/pdf/1907.01826.pdf) - Duan, B., Wang, W., Tang, H., Latapie, H., & Yan, Y. (arXiv 2019) [[code]](https://github.com/tuffr5/CAR-GAN)
* [Visual to Sound: Generating Natural Sound for Videos in the Wild](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Visual_to_Sound_CVPR_2018_paper.pdf) - (Zhou, Y., Wang, Z., Fang, C., Bui, T., & Berg, T. L. (CVPR 2018))[[project page]](http://bvision11.cs.unc.edu/bigpen/yipin/visual2sound_webpage/visual2sound.html)
* [Image generation associated with music data](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Qiu_Image_Generation_Associated_CVPR_2018_paper.pdf) - Qiu, Y., & Kataoka, H. (CVPRW 2018)
* [CMCGAN: A uniform framework for cross-modal visual-audio mutual generation](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17153/16274) - Hao, W., Zhang, Z., & Guan, H. (AAAI 2018) 
#### Multi-modal Architectures
* [What Makes Training Multi-Modal Networks Hard?](https://arxiv.org/pdf/1905.12681.pdf) - Wang, W., Tran, D., & Feiszli, M. (ArXiv 2019) 
* [MFAS: Multimodal Fusion Architecture Search](http://openaccess.thecvf.com/content_CVPR_2019/papers/Perez-Rua_MFAS_Multimodal_Fusion_Architecture_Search_CVPR_2019_paper.pdf) - Pérez-Rúa, J. M., Vielzeuf, V., Pateux, S., Baccouche, M., & Jurie, F. (CVPR 2019)

#### Uncategorized Papers
* [Sight to sound: An end-to-end approach for visual piano transcription](http://www.robots.ox.ac.uk/~vgg/publications/2020/Koepke20/koepke20.pdf) - Koepke, A. S., Wiles, O., Moses, Y., & Zisserman, A. (ICASSP 2020) [[project page/dataset]](https://www.robots.ox.ac.uk/~vgg/research/sighttosound/)
* [Solos: A Dataset for Audio-Visual Music Analysis](https://arxiv.org/pdf/2006.07931.pdf) - Montesinos, J. F., Slizovskaia, O., & Haro, G. (arXiv 2020) [[project page]](https://www.juanmontesinos.com/Solos/) [[dataset]](https://github.com/JuanFMontesinos/Solos)
* [Cross-Task Transfer for Multimodal Aerial Scene Recognition](https://arxiv.org/pdf/2005.08449.pdf) - Hu, D., Li, X., Mou, L., Jin, P., Chen, D., Jing, L., ... & Dou, D. (arXiv 2020) [[code]](https://github.com/DTaoo/Multimodal-Aerial-Scene-Recognition) [[dataset]](https://zenodo.org/record/3828124)
* [STAViS: Spatio-Temporal AudioVisual Saliency Network](http://openaccess.thecvf.com/content_CVPR_2020/papers/Tsiami_STAViS_Spatio-Temporal_AudioVisual_Saliency_Network_CVPR_2020_paper.pdf) - Tsiami, A., Koutras, P., & Maragos, P. (CVPR 2020) [[code]](https://github.com/atsiami/STAViS)
* [AlignNet: A Unifying Approach to Audio-Visual Alignment](http://openaccess.thecvf.com/content_WACV_2020/papers/Wang_AlignNet_A_Unifying_Approach_to_Audio-Visual_Alignment_WACV_2020_paper.pdf) - Wang, J., Fang, Z., & Zhao, H. (WACV 2020) [[project page]](https://jianrenw.github.io/AlignNet/) [[code]](https://github.com/zfang399/AlignNet)
* [Self-supervised Moving Vehicle Tracking with Stereo Sound](http://openaccess.thecvf.com/content_ICCV_2019/papers/Gan_Self-Supervised_Moving_Vehicle_Tracking_With_Stereo_Sound_ICCV_2019_paper.pdf) - Gan, C., Zhao, H., Chen, P., Cox, D., & Torralba, A. (ICCV 2019) [[project page/dataset]](http://sound-track.csail.mit.edu/)
* [Vision-Infused Deep Audio Inpainting](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Vision-Infused_Deep_Audio_Inpainting_ICCV_2019_paper.pdf) - Zhou, H., Liu, Z., Xu, X., Luo, P., & Wang, X. (ICCV 2019) [[project page]](https://hangz-nju-cuhk.github.io/projects/AudioInpainting) [[code]](https://github.com/Hangz-nju-cuhk/Vision-Infused-Audio-Inpainter-VIAI)
* [ISNN: Impact Sound Neural Network for Audio-Visual Object Classification](http://openaccess.thecvf.com/content_ECCV_2018/papers/Auston_Sterling_ISNN_-_Impact_ECCV_2018_paper.pdf) - Sterling, A., Wilson, J., Lowe, S., & Lin, M. C. (ECCV 2018) [[project page]](http://gamma.cs.unc.edu/ISNN/) [[dataset1]](https://drive.google.com/drive/folders/1lVYYMTOLItozaU-vAa0OoXQr_4VfmqVg?usp=sharing)[[dataset2]](https://drive.google.com/drive/folders/1p0HAlrsoydYFuWginPuhiDQjncAvSQon?usp=sharing) [[model]](http://gamma.cs.unc.edu/ISNN/ModelNet_URLs_WAV_PLY.pdf)
* [Audio to Body Dynamics](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shlizerman_Audio_to_Body_CVPR_2018_paper.pdf) - Shlizerman, E., Dery, L., Schoen, H., & Kemelmacher-Shlizerman, I. (CVPR 2018) [[project page]](https://arviolin.github.io/AudioBodyDynamics/)[[code]](https://github.com/facebookresearch/Audio2BodyDynamics)
* [A Multimodal Approach to Mapping Soundscapes](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w49/Salem_A_Multimodal_Approach_CVPR_2018_paper.pdf) - Salem, T., Zhai, M., Workman, S., & Jacobs, N. (CVPRW 2018) [[project page]](http://cs.uky.edu/~salem/audio-mapping/)
* [Shape and material from sound](https://papers.nips.cc/paper/6727-shape-and-material-from-sound.pdf) - Zhang, Z., Li, Q., Huang, Z., Wu, J., Tenenbaum, J., & Freeman, B. (NeurIPS 2017)

## Datasets
#### General Audio-Visual Tasks
* [AudioSet](https://research.google.com/audioset/) - Audio-Visual Classification
* [MUSIC](https://github.com/roudimit/MUSIC_dataset) - Audio-Visual Source Separation
* [AudioSetZSL](https://github.com/krantiparida/AudioSetZSL) - Audio-Visual Zero-shot Learning
* [Visually Engaged and Grounded AudioSet (VEGAS)](http://bvision11.cs.unc.edu/bigpen/yipin/visual2sound_webpage/visual2sound.html) - Sound generation from video
* [SoundNet-Flickr](http://soundnet.csail.mit.edu/) - Image-Audio pair for cross-modal learning
* [Audio-Visual Event (AVE)](https://sites.google.com/view/audiovisualresearch) - Audio-Visual Event Localization
* [AudioSet Single Source](http://vision.cs.utexas.edu/projects/separating_object_sounds/#data) - Subset of AudioSet videos containing only a single souding object
* [Kinetics-Sounds](https://arxiv.org/pdf/1705.08168.pdf) - Subset of Kinetics dataset
* [EPIC-Kitchens](https://epic-kitchens.github.io/2019) - Egocentric Audio-Visual Action Recogniton
* [Audio-Visually Indicated Actions Dataset](https://pavis.iit.it/datasets/audio-visually-indicated-actions-dataset) - Multimodal dataset (RGB, acoustic data as raw audio) acquired using the acoustic-optical camera 
* [IMSDb dataset](https://www.robots.ox.ac.uk/~vgg/research/speech2action/) - Movie scripts downloaded from The [Internet Script Movie Database](https://www.imsdb.com)
* [YOUTUBE-ASMR-300K dataset](https://karreny.github.io/telling-left-from-right/) -  ASMR videos collected from YouTube that contains stereo audio
* [FAIR-Play](https://github.com/facebookresearch/FAIR-Play) - 1,871 video clips and their corresponding binaural audio clips recorded in a music room
* [VGG-Sound](http://www.robots.ox.ac.uk/~vgg/data/vggsound/) - audio-visual correspondent dataset consisting of short clips of audio sounds, extracted from videos uploaded to YouTube
#### Face-Voice Dataset
* [VoxCeleb](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/) - Audio-Visual Speaker Identification, contains two versions
* [EmoVoxCeleb](http://www.robots.ox.ac.uk/~vgg/research/cross-modal-emotions/)
* [Speech2Gesture](http://people.eecs.berkeley.edu/~shiry/projects/speech2gesture/) - Gesture prediction from speech
* [AVSpeech](https://looking-to-listen.github.io/avspeech/)
* [LRW Dataset](http://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)



## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Kranti Kumar Parida](https://krantiparida.github.io/) has waived all copyright and related or neighboring rights to this work.

## Contributing
Please feel free to send me [pull requests](https://github.com/krantiparida/awesome-audio-visual/pulls) or email (kranti@cse.iitk.ac.in) to add links, correct wrong ones or if you find any broken links.