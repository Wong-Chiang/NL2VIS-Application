# NL2VIS-Application

实现一个使用自然语言作为输入，结合database，能够利用InternLM自动进行可视化图表生成的工具。
使用InternLM大模型的能力进行NL2VQL的直接转换，同时利用LLM的推理能力进行相关可视化代码的生成，代码可以在沙盒中自动化运行，并利用MLLM如InternVL检测结果的合理性、有效性以及可读性。

工具应当具备：可视化界面、可自定义的database(暂定sqlite数据库)、中间环节（推理、VQL生成、代码生成、运行检测）的可视化流程展示、加入Feedback收集。

挑战：1. 一次生成多组用于挑选 2. 引入对话，根据用户需求进行微调 3. 自动化的评分体系

参考：

[1] Luo Y, Tang J, Li G. nvBench: A large-scale synthesized dataset for cross-domain natural language to visualization task[J]. arXiv preprint arXiv:2112.12926, 2021.

[2] Chen N, Zhang Y, Xu J, et al. Viseval: A benchmark for data visualization in the era of large language models[J]. IEEE Transactions on Visualization and Computer Graphics, 2024.

[3] Ouyang G, Chen J, Nie Z, et al. nvAgent: Automated Data Visualization from Natural Language via Collaborative Agent Workflow[J]. arXiv preprint arXiv:2502.05036, 2025.
