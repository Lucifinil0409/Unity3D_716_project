# Unity3D_716_project
**由于Github无法上传大于100M的资源文件，只好写一下项目总结了**

**Demo视频展示**
![go to video](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/716%E8%88%B0%E8%88%B9%E6%A8%A1%E6%8B%9F%E9%A1%B9%E7%9B%AE%20-%20%E5%9B%BE%E5%BD%A2%E6%8A%80%E6%9C%AFwiki.mp4)

**军事需求（从项目报告里摘的hhh）**

   战场态势，指作战双方各作战要素的所处状态、变化与发展趋势。“态”，强调当前状态，是对作战要素当前位置、运动参数、身份属性、类型等的描述；“势”，强调发展趋势，是对隐含的作战意图、作战能力、相互关系以及对我方构成威胁等的分析，包括军队作战任务和作战企图、行军路线、兵力部署、火力计划、阵地编成、战斗队形等内容。全面准确的掌握战场态势，是正确决策和占据战场主动的前提，是决胜战场的必要条件。  
    然而，伴随信息化技术的发展，现代战争形态正在发生着巨大的变化。现在战场空间变得越来越复杂，战争范围由传统的三维空间拓展到陆、海、空、天、电、网多维空间。现代战争更加注重作战体系的对抗，以信息化战场为依托，众多人员、武器装备、作战系统等在物理空间、电磁空间、虚拟空间相互关联、相互耦合，构成了一个极其复杂、庞大的作战体系，战场态势高度复杂。同时，随着新概念武器装备的不断列装、全新作战理论与作战样式的不断涌现，不断颠覆现有战争模式，对未来战争造成更大的不确定性。现在战争战场呈现出“高复杂度、高对抗、高动态、多时空、不确定”的特性。如何确保指挥员在高复杂度、高对抗、高负荷的战场环境下，面对关键信息不充足的情况，对大量态势信息进行高效、准确的分析，从中获取有用信息、形成正确认知、迅速做出决策成为现代战争亟需解决的问题。   
   作战态势分析涉及到作战指挥的各个环节，本项目以联合作战推演中的态势分析任务为背景，研究辅助指挥员进行高效、准确态势分析的新思路、新方法。联合作战推演是在作战行动实施前或者实施过程中，按照作战筹划方案规定的作战意图、顺序和进程，对作战方案中不同作战阶段的部署、行动所达成的态势、目标或者结果进行演练分析的过程。考虑到联合作战方案筹划的系统性和复杂性，迫切需求对联合作战方案进行推演验证，为战略战役作战决策提供辅助手段。联合作战推演中，指挥员不能仅凭大脑构想和思维简单推理，而必须是在可视化分析环境中，将联合作战筹划的内容、战场环境、战场综合态势、作战过程等进行更加形象的展现，借助人工智能分析辅助、人机智能融合交互技术，对关键作战问题进行试验、验证和推演，及时做出调整和优化，从而形成作战构想和作战计划。
   然而当前在联合作战推演中进行高效、准确态势，缺乏针对空间结构化战场态势空间的动态高效可视化表征方式。结构化信息，是指信息经过分析后可分解成多个相互关联的组成部分，各组成部分间有明确的层次结构，战场态势空间是战场态势要素及其相互关系的集合，具有高度空间结构化的特性。信息化战争情况下，各作战要素相互关联、相互耦合，战场态势愈加复杂。依靠传统的以二维显示技术为主的信息记录和呈现方式，只能够记录和再现战场态势空间某个角度的信息，难以实现对高度复杂的高度空间结构化战场态势要素及其相互关系的高效可视化表征，增加了指挥员认知态势的成本。
   为实现结构化战场态势空间的动态高效可视化表征，促进人机之间的高效交互感知，减轻指挥员的认知负荷，北京邮电大学提出采用裸眼真三维光场显示技术进行三维态势信息可视化展示。真三维光场显示通过构建包含多个方向光线信息的空间体像素实现对客观世界场景的真实再现，能够还原三维场景的深度、亮度、色彩、对比度等多个维度的信息。研究裸眼真三维光场显示设备，并应用于指控系统，可实现三维战场态势分布的真三维展示，充分的展示了三维战场态势分布的深度信息，提高了三维信息展示的组织性和结构性，有助于提高三维态势信息的感知、决策、判断的效率及准确度，降低指挥员的认知负荷，提高指控系统的作战效能。


**设备功能：**

裸眼三维可视化设备是以国产化元器件为主，重点演示基于光场显示的裸眼三维态势可视化功能及性能。具体功能如下：

(1)支持三维场景的裸眼三维光场显示；

(2)支持多元态势元素的高效渲染（包括舰艇、导弹、海面、锡箔云等）；

(3)支持手势识别技术（LeapMotion控制）。

**场景实现：**

海洋

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E6%B5%B7%E6%B4%8B.png)

岛屿

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E5%B2%9B%E5%B1%BF.png)

舰船

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E8%88%AA%E6%AF%8D.png)

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E6%88%98%E8%88%B0.png)

小规模海战模拟作为示范应用场景，应用光场可视化指挥作战。整体场景分为两部分：
（1）双方舰队战上遭遇战
（2）舰船的细节显示
场景还应包含三维岛屿，并能够展示岛屿植被信息。双方舰队遭遇时，红方舰船能够主动发射导弹攻击蓝方舰船，蓝方舰船能够开启导弹防御措施拦截或规避导弹的袭击。软件能够模拟蓝方舰船受到攻击后损坏情况，并进行光场可视化展示。舰船的细节展示应当采用自然交互方式，整个场景应当实时的光场可视化操作。

海战模拟场景界面：

2D：

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E6%B5%B7%E6%88%98%E6%A8%A1%E6%8B%9F%E5%9C%BA%E6%99%AF.png)

3D：

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E6%B5%B7%E6%88%98%E6%A8%A1%E6%8B%9F%E5%9C%BA%E6%99%AF_3D.png)

舰船细节场景界面：

2D：

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E8%88%B0%E8%88%B9%E7%BB%86%E8%8A%82%E5%9C%BA%E6%99%AF.png)

3D：

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E8%88%B0%E8%88%B9%E7%BB%86%E8%8A%82%E5%9C%BA%E6%99%AF_3D.png)

场景切换界面：

![image](https://github.com/Lucifinil0409/Unity3D_716_project/blob/master/ShowPic/%E5%9C%BA%E6%99%AF%E5%88%87%E6%8D%A2.png)
