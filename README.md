# DeepMoleNet

Transferable Multi-level Attention Neural Network for Accurate Prediction of Quantum Chemistry Properties via Multi-task Learning

Champion solution of Coalab Alchemy Contest 
<br>https://alchemy.tencent.com/  
  

DeepMoleNet is a deep learning package for molecular properties prediction. This code is developed by Ziteng Liu@Nanjing Univerisity and Liqiang Lin@Nanjing University during Colab Alchemy Contest https://alchemy.tencent.com/. We setup one team called "NJU_Chem" and won the champion in the competition. We also released document to disclose our thoughts during different stages after winning. Former DeepMoleNet was called ape-MPNN in the contest. Please see https://alchemy.tencent.com/data/2019/1st_solution-ape-MPNN_NJU_Chem.pdf for detail. 

![image](https://github.com/Frank-LIU-520/DeepMoleNet/blob/main/alchemy.png)

The ideas come from the discussion with our friends (starcraft Ⅱ lovers) at the cafe shop (called Mole Cafe) in school of chemistry and chemical engineering building. So later we both decide to rename ape-MPNN to DeepMoleNet to remember this time our school time (my 2nd Ph.D. and his sophomore year).

To cite this algorithm, please reference: Liu, Ziteng, et al. "Transferable multi-level attention neural network for accurate prediction of quantum chemistry properties via multi-task learning." ChemRxiv 12588170 (2020): v1.

1 unzip the zip file and make sure all packagement in the requirement.txt file are installed;

2 put molecule sdf files in the .\data-bin\raw\dev, with its sdf file name and all 12 properties saved in .\data-bin\raw\dev_target.csv in templet.

3 run the code, python DeepMoleNet.py

Please contact njuziteng@hotmail.com if you have any questions.
