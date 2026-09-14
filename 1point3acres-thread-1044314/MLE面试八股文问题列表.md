# [求米]MLE面试的八股文问题列表

> 原帖作者：stonepeter  
> 原帖时间：2024-02-10 12:52:01  
> 版块：求职（非面经）  
> 原始链接：[一亩三分地帖子 1044314](https://www.1point3acres.com/home/thread/1044314)  
> 旧版公开链接：[thread-1044314-1-1.html](https://www.1point3acres.com/bbs/thread-1044314-1-1.html)  
> 整理日期：2026-09-14

## 完整性说明

- 本文件整理主楼正文和匿名公开页面中可见的全部回复；网页导航、广告、用户积分栏、评分名单和站点水印未收录。
- 页面顶部显示“回复：4”，但匿名公开页面实际只渲染出 3 条可见回复（主楼之外的 3 个帖子块）。未显示的 1 条回复可能已删除、审核隐藏，或属于计数缓存差异，无法从公开页面恢复。
- 原网页中断裂的 F1 公式已按其上下文恢复为标准 Markdown/LaTeX 写法；其余内容仅做段落、列表和标点排版。
- 内容版权归原作者及一亩三分地所有；本文件保留作者和原帖链接，请依照原网站转载规则使用。

---

## 主楼

求米看面经。

常常听到 MLE 面试的时候被问到“八股”文面试题，这些“八股”文面试题对于刚刚从 Machine Learning 专业毕业的学生，可能会很容易；对于工作中常用的内容，也会很熟悉。但是有些概念和内容可能随着工作时间的增加，都忘记了。

下面是这些可能问题的列表。（我根据个人体会简单地备注一下）

- 什么是机器学习？它和传统编程有什么不同？
- 解释监督学习、非监督学习和强化学习的区别。
- 描述决策树算法及其如何工作。（重要）
- 解释什么是随机森林和它的工作原理。（常见）
- 线性回归和逻辑回归的区别是什么？
- 什么是支持向量机（SVM）？它是如何工作的？
- 解释梯度下降算法及其变种。（重要）
- 什么是神经网络？它是如何工作的？
- 描述卷积神经网络（CNN）和它们在图像处理中的应用。
- 什么是循环神经网络（RNN）？它们和 CNN 有什么不同？
- 解释过拟合和欠拟合，以及如何解决这些问题。（重要，常见）
- 什么是交叉验证？它为什么重要？
- 描述主成分分析（PCA）及其用途。
- 什么是批量归一化（Batch Normalization）？
- ReLU 激活函数相比于 Sigmoid 有什么优势？（常见）
- 解释非线性激活函数的重要性。
- 什么是正则化？举例说明 L1 和 L2 正则化。
- 解释深度学习中的 dropout 技术。
- 描述长短期记忆网络（LSTM）和它们的应用。
- 机器学习模型评估有哪些常用指标？（常见）
- 什么是特征工程？为什么它在机器学习中很重要？
- 描述 K-最近邻（K-NN）算法及其工作原理。
- 什么是梯度消失/爆炸问题？如何解决它？
- 什么是集成学习？常见的集成学习方法有哪些？
- 解释偏差-方差权衡（Bias-Variance Tradeoff）。
- 描述 K 均值聚类算法及其应用。
- 什么是自编码器？它在深度学习中的作用是什么？
- 如何处理不平衡数据集？（常见）
- 什么是学习率？它为何重要？（常见）
- 解释协同过滤和它在推荐系统中的应用。
- 什么是深度学习中的注意力机制？
- 描述生成对抗网络（GAN）及其工作原理。
- 什么是时间序列分析？举例说明其应用。
- 如何评价一个机器学习模型的性能？
- 解释 ROC 曲线和 AUC 指标。（重要）
- 描述贝叶斯网络及其在机器学习中的应用。
- 什么是强化学习中的 Markov 决策过程（MDP）？
- 解释 NLP 中的词嵌入（例如 Word2Vec）。
- 什么是模型泛化？如何提高模型的泛化能力？
- 什么是数据预处理，并举例其重要性。
- 描述词袋（Bag of Words）模型及其局限性。
- 解释 TF-IDF（词频-逆文档频率）是什么，以及它的应用。（常见）
- 什么是语言模型？举例说明其在 NLP 中的应用。
- 描述一下序列到序列（Seq2Seq）模型及其应用。
- 什么是长短期记忆网络（LSTM）？它在 NLP 中是如何使用的？
- 解释注意力机制（Attention Mechanism）在 NLP 中的作用。
- 什么是 BERT？它在 NLP 中的重要性是什么？
- 描述 Transformer 模型及其在 NLP 中的应用。
- 什么是 Word Embedding？举例说明如何使用它。（重要）
- 解释 NLP 中的命名实体识别（NER）。
- 描述情感分析的方法和挑战。
- 如何处理 NLP 中的多语言问题？
- 什么是对话系统（Chatbots）？如何构建一个有效的对话系统？
- 解释自然语言生成（NLG）和自然语言理解（NLU）的区别。
- 描述一下机器翻译的基本原理和挑战。
- 什么是文本分类？它在实际中有哪些应用？
- 在 NLP 中如何进行文本相似度的计算？
- 解释 NLP 中的词性标注（POS Tagging）。
- 描述如何处理 NLP 中的语言歧义问题。
- 什么是计算机视觉（Computer Vision）？它在机器学习中的作用是什么？
- 描述图像分类和对象识别的差异。
- 解释图像分割与实例分割的区别。
- 什么是边缘检测？它在图像处理中的应用是什么？
- 解释什么是图像增强（Image Augmentation）及其为什么重要。
- 什么是 YOLO（You Only Look Once）算法？它是如何进行实时对象检测的？
- 描述区域卷积神经网络（R-CNN）及其变种。
- 什么是深度学习在图像识别中的应用？
- 如何评估计算机视觉模型的性能？
- 解释光流法（Optical Flow）在视频处理中的应用。
- 描述 GAN（生成对抗网络）在图像生成中的应用。
- 什么是图像的超分辨率？
- 描述在自动驾驶车辆中使用的计算机视觉技术。
- 什么是面部识别系统？它是如何工作的？
- 解释图像中的对象跟踪技术。
- 描述深度学习在医学图像处理中的应用。
- 如何处理图像数据的噪声和扭曲？

欢迎大家补充！！！

请大家顺手加米，点赞！

### 补充内容（2024-02-11 07:01 +08:00）

以下是几个作者认为常见和重要的问题的参考回答。

#### 描述决策树算法及其如何工作。（重要）

A decision tree is a machine learning algorithm that creates a tree-like model of decisions by splitting data based on certain criteria, used for both classification and regression tasks.

#### 解释什么是随机森林和它的工作原理。（常见）

A Random Forest is an ensemble machine learning method that builds multiple decision trees with random subsets of data and features, and makes predictions based on the majority vote or average of these trees, thereby improving accuracy and reducing overfitting.

#### 解释过拟合和欠拟合，以及如何解决这些问题。（重要，常见）

Overfitting is when a model learns the training data too well, including noise, leading to poor performance on new data, while underfitting occurs when a model is too simple to capture the data's complexity, with solutions including adjusting model complexity, data augmentation, regularization, and feature engineering.

#### ReLU 激活函数相比于 Sigmoid 有什么优势？（常见）

ReLU activation function is preferred over sigmoid in neural networks due to its computational efficiency, ability to mitigate the vanishing gradient problem, and tendency to create sparser and more efficient networks.

#### 机器学习模型评估有哪些常用指标？（常见）

For classification tasks, common metrics include Accuracy (overall correctness), Precision and Recall (correct positive predictions relative to the predicted positives and all actual positives respectively), F1 Score (balance between Precision and Recall), and AUC-ROC (measure of the ability to distinguish between classes).

In regression tasks, key metrics are Mean Absolute Error (average absolute difference between predicted and actual values), Mean Squared Error and Root Mean Squared Error (average of squared differences and its square root, respectively), and R-squared (proportion of variance in the dependent variable explained by the predictors).

#### 如何处理不平衡数据集？（常见）

To handle imbalanced datasets, techniques such as resampling (oversampling minority class or undersampling majority class), using algorithms robust to imbalance, applying cost-sensitive training, choosing appropriate evaluation metrics, considering anomaly detection methods, collecting more data, and employing ensemble methods can be effective.

#### 什么是学习率？它为何重要？（常见）

The learning rate is a crucial hyperparameter in machine learning that controls the size of weight updates during training, influencing the balance between convergence speed and accuracy, and preventing overfitting or underfitting.

#### 解释 ROC 曲线和 AUC 指标。（重要）

The ROC curve is a graphical representation of a classification model's performance, plotting the True Positive Rate against the False Positive Rate at various thresholds, while the AUC is a single number summary of the ROC curve, indicating the probability that the model correctly distinguishes between a randomly chosen positive and a negative example.

#### 解释 NLP 中的词嵌入（例如 Word2Vec）。

Word Embedding in NLP involves mapping words or phrases to vectors of real numbers in a lower-dimensional space, capturing semantic and syntactic meanings and relationships, significantly enhancing the machine's ability to understand and process language.

#### 解释 TF-IDF（词频-逆文档频率）是什么，以及它的应用。（常见）

TF-IDF is a statistical measure used in text analysis that combines Term Frequency (how often a word appears in a document) with Inverse Document Frequency (which reduces the weight of commonly used words across documents) to determine the importance or relevance of words in a document within a larger corpus.

### 补充内容（2024-05-01 22:56 +08:00）

#### 1. Explain the bias and variance tradeoff.（重要、常见）

Bias and variance are two types of error in machine learning models. Bias refers to the error introduced by approximating a real-world problem, which may be complex, with a model that is too simple. High bias can cause the model to miss relevant relations between features and target outputs (underfitting). Variance refers to the model's sensitivity to small fluctuations in the training set.

High variance can cause modeling the random noise in the training data, rather than the intended outputs (overfitting).

The tradeoff is that improving one typically increases the other. Reducing bias generally makes the model more complex, increasing the risk of fitting noise in the training data (higher variance). Conversely, simplifying the model to reduce variance can increase bias, making it less accurate on the training data.

#### 2. In a classification model, if you can only choose one metric, what would it be, and why?（重要）

Choosing one metric depends largely on the problem context, but a commonly effective and balanced metric is the F1 Score. The F1 score is the harmonic mean of precision and recall, providing a balance between the two. It is particularly useful in scenarios where there are imbalanced classes or when both false positives and false negatives are costly.

#### 3. What's the difference between Gradient Boosting Tree and Random Forest?（常见）

Gradient Boosting Tree (GBT) and Random Forest are both ensemble learning methods that use decision trees, but they differ significantly in approach:

- Random Forest builds multiple decision trees (forest) and outputs the mode of the classes (classification) or mean prediction (regression) of the individual trees. It reduces variance by averaging multiple deep decision trees, each trained on a different sample of the same training set. It generally provides a robust performance by decorrelating the trees, especially when trees are deep.
- Gradient Boosting Tree builds trees one at a time, where each new tree helps to correct errors made by previously trained tree. Unlike Random Forest, which builds each tree independently, Gradient Boosting Trees build trees sequentially with each tree trying to correct the errors of the previous ones. This approach focuses more on reducing bias, but can be more susceptible to overfitting if not properly tuned or if too many trees are used.

#### 4. What's F1 score's equation?（重要）

The F1 score is calculated using the following equation:

$$
F1 = 2 \times \frac{\text{precision} \times \text{recall}}{\text{precision} + \text{recall}}
$$

where precision is the ratio of correctly predicted positive observations to the total predicted positives, and recall is the ratio of correctly predicted positive observations to all observations in the actual class.

#### 5. When two thresholds have the same F1 score, why and how to decide which one to use?

If two thresholds result in the same F1 score, other factors must be considered to make a decision, such as:

- Business or clinical relevance: Depending on the application, one might prefer to prioritize precision (e.g., in a spam filter) or recall (e.g., in cancer detection).
- Cost of false positives vs. false negatives: Analyze which error type is more costly or risky and choose the threshold accordingly.

#### 6. Give two examples of activation functions, talk about their pros and cons.（重要、常见）

ReLU (Rectified Linear Unit):

- Pros: Prevents vanishing gradient problem, accelerates the convergence of stochastic gradient descent compared to sigmoid or tanh functions.
- Cons: Can lead to dying ReLU problem where neurons only output zeros due to negative inputs.

Sigmoid:

- Pros: Useful for models where we need to predict the probability as an output since the output is in the range (0, 1).
- Cons: Prone to vanishing gradient problem, not zero-centered output, which can affect the convergence during training.

#### 7. Give two examples of gradient update methods, talk about their pros and cons.（常见）

Stochastic Gradient Descent (SGD):

- Pros: Can converge fast and is also computationally efficient with large datasets.
- Cons: Can be noisy due to the update performed on each example, which can cause the loss function to fluctuate heavily.

Adam (Adaptive Moment Estimation):

- Pros: Combines the advantages of two other extensions of SGD, AdaGrad and RMSProp. Handles sparse gradients on noisy problems very well.
- Cons: May require more memory to store the gradients and squared gradients for each parameter and can be biased towards the initial gradients.

---

## 可见回复

### 回复 1

> 作者：阿威  
> 时间：2024-02-14 03:22:30

真的是好贴

### 回复 2（楼主）

> 作者：stonepeter  
> 时间：2024-05-01 22:58:17  
> 编辑记录：本帖最后由 stonepeter 于 2024-05-01 07:59 编辑

此回复完整重发了主楼“补充内容（2024-05-01 22:56 +08:00）”中的 7 组问题与回答；为保留评论信息且避免同一大段内容重复两遍，本文件以上一节的完整文本为准。

### 回复 3

> 作者：KaylaXieGDOH  
> 时间：2025-07-08 12:57:51

谢谢分享！

### 页面统计中未公开显示的回复

页面统计比公开渲染出的回复多 1 条。由于该内容未出现在匿名公开页面中，本文件不臆测其作者、时间或正文。
