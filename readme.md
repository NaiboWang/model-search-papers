# Model Search Paper Repository

This is a repository contains papers about model search for future transfer learning/fine tune, the problem aims to filter and search pre-trained models before stepping into the real fine-tuning process on the downstream/target task/dataset.

## Latest Papers

-   Renggli, Cedric, et al. ["Which model to transfer? finding the needle in the growing haystack."](papers/Which%20model%20to%20transfer.pdf) CVPR2022. [[Supplementary Materials]](papers/Which%20model%20to%20transfer_supplementary.pdf)
-   Renggli, Cedric, et al. ["SHiFT: An Efficient, Flexible Search Engine for Transfer Learning."](papers/SHiFT%20An%20Efficient,%20Flexible%20Search%20Engine%20for%20Transfer%20Learning%20-%202022%20-%20Unknown%20-%20Renggli%20et%20al.pdf) arXiv preprint arXiv:2204.01457 (2022).

## Benchmarks and preliminary research

This section contains some benchmarks/datasets settings which are commonly used in model search/transfer learning papers.

-   Zamir, Amir R., et al. ["Taskonomy: Disentangling task transfer learning."](papers/taskonomy_CVPR2018.pdf) Proceedings of the IEEE conference on computer vision and pattern recognition. 2018. [[Supplementary Materials]](papers/taskonomy_supp_CVPR2018.pdf)
-   Kornblith, Simon, Jonathon Shlens, and Quoc V. Le. ["Do better imagenet models transfer better?."](papers/Do%20better%20imagenet%20models%20transfer%20better%20-%202019%20-%20Proceedings%20of%20the%20IEEE%20Computer%20Society%20Conference%20on%20Computer%20Vision%20and%20Pattern%20Re.pdf) Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2019.
-   Zhai, Xiaohua, et al. ["The visual task adaptation benchmark."](papers/the_visual_task_adaptation_ben.pdf) (2019).

## Existing works

This section contains papers in the past years about model search or transferability measurement methods.

### Task Agnostic Search

These strategies rank models without looking at the data of the downstream task.

-   Qiang, Zhangcheng, et al. ["MobileDLSearch: Ontology-based Mobile Platform for Effective Sharing and Reuse of Deep Learning Models."](papers/MobileDLSearch%20Ontology-based%20Mobile%20Platform%20for%20Effective%20Sharing%20and%20Reuse%20of%20Deep%20Learning%20Models%20-%202022%20-%202021%20IEEE%20International%20C.pdf) *2021 IEEE International Conferences on Internet of Things (iThings) and IEEE Green Computing & Communications (GreenCom) and IEEE Cyber, Physical & Social Computing (CPSCom) and IEEE Smart Data (SmartData) and IEEE Congress on Cybermatics (Cybermatics)*. IEEE, 2021.
-   Sparks, Evan R., et al. ["Automating model search for large scale machine learning."](papers/Automating%20model%20search%20for%20large%20scale%20machine%20learning%20-%202015%20-%20ACM%20SoCC%202015%20-%20Proceedings%20of%20the%206th%20ACM%20Symposium%20on%20Cloud%20Computin.pdf) Proceedings of the Sixth ACM Symposium on Cloud Computing. 2015.
-   Kornblith, Simon, Jonathon Shlens, and Quoc V. Le. ["Do better imagenet models transfer better?."](papers/Do%20better%20imagenet%20models%20transfer%20better%20-%202019%20-%20Proceedings%20of%20the%20IEEE%20Computer%20Society%20Conference%20on%20Computer%20Vision%20and%20Pattern%20Re.pdf) Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2019.

### Task Aware Search

Task-aware methods use the downstream data to select models, thus requiring additional computation.

-   Ueno, Yosuke, and Masaaki Kondo. ["A Base Model Selection Methodology for Efficient Fine-Tuning."](papers/A%20BASE%20MODEL%20SELECTION%20METHODOLOGY%20FOR%20EFFICIENT%20FINE-TUNING.pdf) (2019).
-   Puigcerver, Joan, et al. ["Scalable Transfer Learning with Expert Models."](papers/Scalable%20Transfer%20Learning%20with%20Expert%20Models%20-%20ICLR2021%20-%20Puigcerver%20et%20al.pdf) International Conference on Learning Representations. 2020. [[Supplementary Materials]](papers/SUPP%20-%20Scalable%20Transfer%20Learning%20with%20Expert%20Models%20-%202021%20-%20Puigcerver%20et%20al.pdf)
-   Bao, Yajie, et al. ["An information-theoretic approach to transferability in task transfer learning."](papers/An%20Information-Theoretic%20Approach%20to%20Transferability%20in%20Task%20Transfer%20Learning%20-%202019%20-%20Proceedings%20-%20International%20Conference%20on%20Image.pdf) (H-Score) 2019 IEEE International Conference on Image Processing (ICIP). IEEE, 2019. [[Supplementary Materials]](papers/sup%20-%20An%20Information-Theoretic%20Approach%20to%20Transferability%20in%20Task%20Transfer%20Learning.pdf)
-   Tran, Anh T., Cuong V. Nguyen, and Tal Hassner. ["Transferability and hardness of supervised classification tasks."](papers/Tran_Transferability_and_Hardness_of_Supervised_Classification_Tasks_ICCV_2019_paper.pdf) (NCE) Proceedings of the IEEE/CVF International Conference on Computer Vision. 2019. [[Supplementary Materials]](papers/Tran_Transferability_and_Hardness_ICCV_2019_supplemental.pdf)
-   Nguyen, Cuong, et al. ["Leep: A new measure to evaluate transferability of learned representations."](papers/LEEP%20A%20new%20measure%20to%20evaluate%20transferability%20of%20learned%20representations%20-%202020%20-%2037th%20International%20Conference%20on%20Machine%20Learning,%20IC.pdf) International Conference on Machine Learning. PMLR, 2020. [[Supplementary Materials]](papers/LEEP%20SUPPLEMENTATY.pdf)
-   Deshpande, Aditya, et al. ["A linearized framework and a new benchmark for model selection for fine-tuning."](papers/A%20linearized%20framework%20and%20a%20new%20benchmark%20for%20model%20selection%20for%20fine-tuning%20-%202021%20-%20Unknown%20-%20Deshpande%20et%20al.pdf) arXiv preprint arXiv:2102.00084 (2021).
-   Bolya, Daniel, Rohit Mittapalli, and Judy Hoffman. ["Scalable Diverse Model Selection for Accessible Transfer Learning."](papers/NeurIPS-2021-scalable-diverse-model-selection-for-accessible-transfer-learning-Paper.pdf) Advances in Neural Information Processing Systems 34 (2021). [[Supplementary Materials]](papers/NeurIPS-2021-scalable-diverse-model-selection-for-accessible-transfer-learning-Supplemental.pdf)
-   You, Kaichao, et al. ["Logme: Practical assessment of pre-trained models for transfer learning."](http://ise.thss.tsinghua.edu.cn/~mlong/doc/LogME-Practical-Assessment-of-Pre-trained-Models-for-Transfer-Learning-icml21.pdf) International Conference on Machine Learning. PMLR, 2021.

### Meta-Learned Task Aware Search

Meta-Learned Task-aware methods’ goal is to favor models that perform well on benchmark datasets similar to the downstream one.

-   Cui, Yin, et al[. "Large scale fine-grained categorization and domain-specific transfer learning."](papers/Large%20Scale%20Fine-Grained%20Categorization%20and%20Domain-Specific%20Transfer%20Learning%20-%202018%20-%20Proceedings%20of%20the%20IEEE%20Computer%20Society%20Conferen.pdf) Proceedings of the IEEE conference on computer vision and pattern recognition. 2018.
-   Achille, Alessandro, et al. ["Task2vec: Task embedding for meta-learning."](papers/TASK2VEC%20Task%20Embedding%20for%20Meta-Learning%20-%20Unknown%20-%20Unknown%20-%20Achille%20et%20al.pdf) Proceedings of the IEEE/CVF International Conference on Computer Vision. 2019. [[Supplementary Materials]](papers/Supplementary%20material%20for%20TASK%202%20VEC%20Task%20Embeddings%20for%20Meta-Learning%20-%20Unknown%20-%20Unknown%20-%20Texture%20et%20al.pdf)
-   Dwivedi, Kshitij, and Gemma Roig. ["Representation similarity analysis for efficient task taxonomy & transfer learning."](papers/Representation%20similarity%20analysis%20for%20efficient%20task%20taxonomy%20&%20transfer%20learning%20-%202019%20-%20Proceedings%20of%20the%20IEEE%20Computer%20Society%20Con.pdf) Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2019.
-   Dwivedi, Kshitij, et al. ["Duality diagram similarity: a generic framework for initialization selection in task transfer learning."](papers/Duality%20Diagram%20Similarity%20A%20Generic%20Framework%20for%20Initialization%20Selection%20in%20Task%20Transfer%20Learning%20-%202020.pdf) European Conference on Computer Vision. Springer, Cham, 2020. [[Supplementary Materials]](papers/Duality%20Diagram%20Similarity%20-%20Supp.pdf)
-   Song, Jie, et al. ["Depara: Deep attribution graph for deep knowledge transferability."](papers/Song_DEPARA_Deep_Attribution_Graph_for_Deep_Knowledge_Transferability_CVPR_2020_paper.pdf) Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2020. [[Supplementary Materials]](papers/Song_DEPARA_Deep_Attribution_CVPR_2020_supplemental.pdf)
