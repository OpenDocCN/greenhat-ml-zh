## 前言

![图片](img/common.jpg)

由于深度学习的快速进展，近年来我们见证了机器学习和人工智能的显著扩展。

这项进展令人兴奋，因为如果我们期待这些进步创造新的产业、改造现有产业，并提高全球人民的生活质量，那么它们无疑会带来积极变化。另一方面，技术的不断涌现使得紧跟最新发展变得具有挑战性和耗时。然而，保持与时俱进对使用这些技术的专业人士和组织至关重要。

我写这本书是为了为读者和机器学习从业者提供一种资源，帮助他们提升在该领域的专业知识，并学习一些我认为有用且重要的技术，这些技术在传统和入门教材及课程中常常被忽视。希望你能发现本书是获得新见解和发现可以在工作中实现的新技术的宝贵资源。

### **这本书适合谁？**

探索人工智能和机器学习文献的世界常常让人感觉像是在走钢丝，大多数书籍都位于两端：一端是广泛的初学者介绍，另一端是深入的数学论述。本书在保持易于接近的同时，阐明并讨论了这些领域的重要发展，且不需要高级数学或编程背景。

这本书适合那些有一定机器学习经验、希望学习新概念和技术的人。它非常适合那些已经参加过机器学习或深度学习初学者课程，或者阅读过相关入门书籍的人。（在本书中，我将*机器学习*作为机器学习、深度学习和人工智能的总称。）

### **你能从这本书中获得什么？**

本书采用独特的问答式风格，每一章简短，围绕与机器学习、深度学习和人工智能基本概念相关的中心问题展开。每个问题后面都有解释，并配有若干插图和图表，同时还有练习题来测试你的理解。许多章节还包括进一步阅读的参考资料。这些简短的信息提供了一个愉快的起点，帮助你从机器学习初学者成长为专家。

本书涵盖了广泛的主题。它包括了关于已建立架构（例如卷积网络）的新见解，帮助你更有效地利用这些技术。它还讨论了更先进的技术，如大语言模型（LLMs）和视觉变换器的内部工作原理。即使是经验丰富的机器学习研究人员和从业者也会遇到一些新知识，丰富他们的技术库。

尽管本书将向你展示新概念和新思想，但它并不是一本数学或编程书。在阅读时你不需要解决任何证明或运行任何代码。换句话说，本书是你旅行时的完美伴侣，或者你可以在喜欢的阅读椅上，配着早晨的咖啡或茶，轻松阅读。

### **如何阅读本书**

本书的每一章都是自成一体的，允许你根据需要自由跳跃章节。当一个章节中的概念在其他章节中有更详细的解释时，我会提供章节参考，帮助你填补理解的空白。

然而，各章节之间有一个战略性顺序。例如，关于嵌入的早期章节为后续关于自监督学习和少样本学习的讨论奠定了基础。为了获得最流畅的阅读体验和最全面的内容理解，我建议从头到尾依次阅读本书。

每一章后都有可选的练习，供希望检验自己理解的读者使用，答案键位于书末。此外，关于章节中提到的任何论文或进一步阅读的材料，你可以在该章节的“参考文献”部分找到完整的引用信息。

本书分为五个主要部分，集中讨论当今机器学习和人工智能领域最重要的话题。

**第一部分：神经网络与深度学习** 涵盖了关于深度神经网络和深度学习的一些问题，这些问题并不特定于某个子领域。例如，我们讨论了监督学习的替代方法，以及减少过拟合的技术，这是在使用机器学习模型解决数据有限的现实问题时常见的问题。

**第一章：嵌入、潜在空间与表示**   深入探讨了嵌入向量、潜在向量和表示之间的区别与相似性。阐明了这些概念如何在机器学习中帮助编码信息。

**第二章：自监督学习**    重点介绍自监督学习，这是一种使神经网络能够以监督方式利用大量未标注数据集的方法。

**第三章：少样本学习**    介绍了少样本学习，这是一种针对小型训练数据集量身定制的监督学习技术。

**第四章：彩票票据假说**    探讨了一个观点，即随机初始化的神经网络包含更小、更高效的子网络。

**第五章：通过数据减少过拟合**    解决机器学习中的过拟合问题，讨论了围绕数据增强和利用未标注数据减少过拟合的策略。

**第六章：通过模型修改减少过拟合**    扩展了关于过拟合的讨论，重点介绍了与模型相关的解决方案，如正则化、选择更简单的模型和集成技术。

**第七章：多 GPU 训练范式**    解释了多 GPU 设置中用于加速模型训练的各种训练范式，包括数据并行和模型并行。

**第八章：变换器的成功**    探索了流行的变换器架构，突出其注意力机制、并行化的便捷性以及高参数量等特点。

**第九章：生成性 AI 模型**    提供了深度生成模型的全面概述，这些模型用于生成各种形式的媒体，包括图像、文本和音频。讨论了每种模型类型的优缺点。

**第十章：随机性的来源**    讨论了在训练深度神经网络过程中可能导致训练和推理结果不一致且不可重现的各种随机性来源。虽然随机性可能是偶然的，但也可以通过设计有意引入。

**第二部分：计算机视觉** 侧重于主要与深度学习相关但特定于计算机视觉的主题，其中许多涉及卷积神经网络和视觉变换器。

**第十一章：计算参数数量**    解释了确定卷积神经网络中参数的过程，这对于评估模型的存储和内存需求非常有用。

**第十二章：全连接层与卷积层**    说明了卷积层如何在某些情况下无缝替代全连接层，这对于硬件优化或简化实现非常有用。

**第十三章：视觉变换器的大型训练集**    探讨了视觉变换器为何需要比传统卷积神经网络更大规模的训练集的原因。

**第三部分：自然语言处理** 涉及与文本处理相关的主题，其中许多与变换器架构和自注意力机制相关。

**第十四章：分布假设**    深入探讨了分布假设，这是一种语言学理论，认为在相同上下文中出现的词语往往具有相似的意义，这对于训练机器学习模型具有重要意义。

**第十五章：文本数据增强**    强调了文本数据增强的重要性，这是一种用于人工增加数据集大小的技术，可以帮助提高模型的性能。

**第十六章：自注意力机制**    介绍了自注意力机制，该机制允许神经网络的每个输入片段引用其他部分。自注意力是现代大语言模型中的关键机制。

**第十七章：编码器与解码器式转换器**    讲解了编码器和解码器转换器架构的细微差别，并解释了哪种架构最适合每个语言处理任务。

**第十八章：使用和微调预训练的转换器**    解释了微调预训练的大型语言模型的不同方法，并讨论了它们的优缺点。

**第十九章：评估生成型大语言模型**    列出了用于语言模型的主要评估指标，如困惑度（Perplexity）、BLEU、ROUGE 和 BERTScore。

**第四部分：生产与部署** 涵盖了与实际场景相关的问题，例如提高推理速度和各种类型的分布变化。

**第二十章：无状态训练与有状态训练**    区分了在模型部署中使用的无状态训练和有状态训练方法。

**第二十一章：数据驱动的 AI**    探讨了数据驱动的 AI，这种方法优先考虑通过改进数据集来提升模型性能。与此相对的是传统的以模型为中心的方法，后者强调通过改进模型架构或方法来提升性能。

**第二十二章：加速推理**    介绍了在不调整模型架构或妥协准确性的情况下，提高模型推理速度的技术。

**第二十三章：数据分布变化**    部署后，AI 模型可能会面临训练数据和现实世界数据分布之间的差异，这被称为数据分布变化。这些变化可能会导致模型性能下降。本章对常见的分布变化进行了分类并详细讲解，如协变量变化、概念漂移、标签变化和领域变化。

**第五部分：预测性能与模型评估** 深入探讨了挖掘预测性能的各个方面，例如改变损失函数、设置 *k* 折交叉验证以及处理有限的标注数据。

**第二十四章：泊松回归与有序回归**    强调了泊松回归和有序回归之间的差异。泊松回归适用于遵循泊松分布的计数数据，例如在飞机上感染感冒的次数。相反，有序回归适用于有序类别数据，而不假设类别之间是等距的，例如疾病严重程度。

**第二十五章：置信区间**    深入探讨了为机器学习分类器构建置信区间的方法。回顾了置信区间的目的，讨论了它们如何估计未知的总体参数，并介绍了如正态近似区间、自助法和使用不同随机种子进行再训练等技术。

**第二十六章：置信区间与一致性预测**    讨论了置信区间和一致性预测之间的区别，并将后一者描述为创建预测区间的工具，这些区间以特定的概率覆盖实际结果。

**第二十七章：合适的度量**    聚焦于数学和计算机科学中合适度量的基本属性。探讨了机器学习中常用的损失函数，如均方误差和交叉熵损失，是否满足这些属性。

**第二十八章：*k*-折交叉验证中的*k***    探讨了*k*-折交叉验证中*k*的作用，并深入分析了选择较大*k*的优缺点。

**第二十九章：训练集与测试集不一致性**    讨论了模型在测试数据集上的表现优于训练数据集的情形。提供了发现和解决训练集与测试集之间差异的策略，介绍了对抗验证的概念。

**第三十章：有限标签数据**    介绍了在数据有限的情况下增强模型表现的各种技术。涵盖了数据标注、自助法，以及如迁移学习、主动学习和多模态学习等范式。

### **在线资源**

我在 GitHub 上提供了可选的补充材料，包含某些章节的代码示例，以增强你的学习体验（见* [`github.com/rasbt/MachineLearning-QandAI-book`](https://github.com/rasbt/MachineLearning-QandAI-book) *）。这些材料设计为实际的扩展和深入探讨书中涉及的主题。你可以在阅读每一章时一起使用它们，或者在阅读后探索它们，以巩固和扩展你的知识。

事不宜迟，让我们深入探讨吧。
