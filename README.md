# Blind-Source-Separation
利用麦克风阵列收集洗衣机信号，根据盲源分离算法将洗衣机信号分离出来，并通过傅里叶变换对比故障信号和正常信号，从而判断洗衣机是否有损坏
根据手头的这个项目记录一些研究过程，记录一下自己的所学所得并尝试联系一下英文表达.

Blind Source Separation is using some altorithms to separarte the mix signal or noise signal. We don't know which signal we need, we don't know how they mix, so we should separate them first. I try to collect some washing siganl based on Haier Washing Machines. Usually it  contains the signals we don't wish. through the ICA or PCA, then separate them. 

Update a new way to process the Single channel blind source separation. Accroding to the EMD, I separated the singnal to some IMFs. then constructed then Mixed matrix with the components and used the ICA. 
BUT there's something wrong with the algorithm, and i should fix it.
