写在前面：以下的所有想法欢迎任何思考和讨论

Preface: All the following thoughts are open to any reflections and discussions
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
第一部分：该项目背后的哲学原理

PART Ⅰ THE PRINCIPLES OF PHILOSOPHY
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
将世界区分为自我与他者，他者愈发清晰，愈发触手可及，对确立自我的要求也就越急迫，进而促成自我的完整和清晰。本算法旨在尽力拟合以整体人类的理性与感性对某一视频做出的反应（为方便叙述，此处的视频作为特定例子代替所有媒介），从而为用户提供一个“大他者”，以最大化用户的福祉。

但与此同时，我们也会牵扯入关于“人的本质是什么”和“如何定义用户的福祉”等哲学讨论之中，这对于启动一个工程来说是不利的，所以我们仅挑选几条关于人和世界的公理（它们有些基于神经认知科学，心理学，社会学，伦理学）作为该算法建立的目的起点和道德起点。与此同时，随着社会的变化，这些作为算法原则的公理也无法避免变动（尽管它们经常是相对不变的），因此我们必须保留对它们进行增删改查的警惕。

以下是这些公理：

1.人存在对某种特定图式结合的偏好（如古典乐中的和弦，视频中前后连贯的转场等），并且这种结合是可被解释的。

2.人从媒介中可获得短期的欢愉和长期的提升，而本算法应当也只应致力于最大化后者。

3.一个媒介存在多维度的符号意义，包括其内容及其本身的形制，无论其意义是易于注意还是容易忽略的，它都存在，并且可以通过人类现有的知识转述。

By dividing the world into self and other, the other becomes increasingly distinct and tangible, thereby heightening the urgency to establish the self and ultimately fostering its integrity and clarity. This algorithm endeavours to approximate the collective rational and emotional response of humanity to a given video (here employed as a representative example of all media for narrative convenience), thereby presenting users with a 'grand other' to maximise their well-being.

However, this inevitably draws us into philosophical debates concerning "the nature of humanity" and "how to define user welfare" – discussions that prove detrimental to launching an engineering project. Therefore, we have selected only a few axioms about humanity and the world (some grounded in neurocognitive science, psychology, sociology, and ethics) to serve as the foundational purpose and ethical starting point for this algorithm. Concurrently, as society evolves, these axioms serving as algorithmic principles inevitably undergo change (though they often remain relatively constant). We must therefore maintain vigilance regarding their potential modification, addition, or deletion.

The axioms are as follows:

1. Humans exhibit preferences for specific combinations of schemata (such as chords in classical music or coherent transitions in video sequences), and these combinations are interpretable.

2. Humans derive both transient gratification and enduring enrichment from media; this algorithm should solely pursue maximising the latter.

3. Every medium possesses multidimensional symbolic meaning—encompassing both its content and its very form—whether readily apparent or subtly concealed. This meaning exists and can be articulated through existing human knowledge.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
第二部分：该算法工作的具体流程（以视频平台为例，初步构想）

PART Ⅱ The specific workflow of the algorithm (using a video platform as an example, preliminary concept)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
算法在系统内部工作，因此，我们需要视频的输入端和输出端。

文字表述：输入→算法→输出

流程图：

```mermaid
graph TD
    A[输入] --> B{算法}
    B --> C[输出]
```

输入部分由输入者输入视频构成，输出端由输出视频被用户接受构成。

文字表述：输入者→输入视频→算法→输出视频→用户

流程图：

```mermaid
graph TD
    A[输入者] --> B{输入视频}
    B --> C[算法]
    C --> D[输出视频]
    D --> E[用户]
```

在算法部分，我们将视频解构分为技术类部分（AI完成）与非技术部分（人类完成）。同时，视频将分为文字，音频，图画部分，这三部分都将作为原始素材进入两个评估体系。具体的评估准则将在[glossary.md](https://github.com/SENKAAD/-Inverse-Entropy-Project-About-A-New-Algorithmn/blob/main/docs/glossary.md)中给出，此处仅举几例以说明为何如此设计。我们先假定此刻算法正在处理一个传统意义上的科教类视频（如关于獾的习性，事实上就像是把维基百科的内容提出来做成字幕配上朗读，再加上一个蓝色的图片作为背景）
