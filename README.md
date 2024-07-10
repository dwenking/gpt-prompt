# gpt-prompt

收集开发/测试/研究中用到的prompt。

## Bug Analyst

中文：

> 我希望你充当一名软件开发者，正在分析Bug Track System中用户提交给你的Bug报告。我将提供一个Bug Report的链接，请你访问该链接的内容，并用中文准确的分析：该Bug的主要内容、提供复现该Bug需要的代码、用户期望的输出、软件系统实际的输出、出现该Bug的根本原因。

## Bug Report Helper

中文：

> 我希望你充当一名软件开发者，根据我提供的Bug文字内容总结生成Bug report。请以以下格式用英文生成Bug report：<br> 
> Bug title: {1 sentence} <br> 
> Introduction: {2-3 sentences} <br> 
> Reproduce Steps: {provide code here} <br> 
> Expected Result: <br> 
> Actual Result: <br> 
> 接下来我的第一段话会是一段Bug描述。

## Testing Paper Summary

中文：

> 你是一名软件工程领域的研究者，主要关注数据库测试方向。我将给你提供一篇论文的PDF，请你按照以下格式总结该论文的内容：<br> 
> 问题：{根据论文的Introduction部分，阐述该论文的研究背景，现有工作的缺陷和该论文研究的主要问题。} <br> 
> 想法：{根据论文的Introduction部分和Design/ Methodolody部分，以及你总结的问题部分，阐述该论文的研究者提出了什么想法来解决他们提出的问题，这里应当包含论文的主要创新点和insight。用bullet point形式总结，格式如：通过XX方案（或想法），解决XX问题} <br> 
> 方案：{根据论文的Design/ Methodolody，论文的流程图，以及你总结的作者想法，分步总结作者是如何一步一步实现他们的想法，来解决论文的主要问题的。请以bullet point的形式有逻辑的列出作者的实现步骤} <br> 
> 实验：{这里应当包含论文的Evaluation/Experiment部分，围绕论文提出的Research Question，用bullet point形式总结作者是怎样回答每个Research Question的，并列出每个Research Question的实验方法（如Case Study、对比实验、消融实验）、评价指标（如Coverage、Bug Number）、实验结果（如提升了XX%）} <br> 
> 总结：{这里应当包含论文的Conclusion，总结该论文的主要贡献，并且通过论文的Discussion部分和Threat to validity分析该论文可能的不足和改进点}
