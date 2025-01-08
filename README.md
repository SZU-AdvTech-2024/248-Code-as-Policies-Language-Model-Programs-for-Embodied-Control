# Code as Policies: Language Model Programs for Embodied Control
## 代码使用说明
 - 在Setup中配置OpenAI的api_key
 - 运行 “Interactive Demo” 下的所有单元格和输入命令。
 - 在Initialize Env中设置方块和碗的数量及颜色
 - 在user_input中输入命令并运行代码。这将通过查询代码生成LLM来编写机器人代码以完成任务，从而将代码作为策略运行。  

 支持的命令：  


 - 空间推理 (e.g. to the left of the red block, the closest corner, the farthest bowl, the second block from the right)
 - 顺序操作 (e.g. put blocks in matching bowls, stack blocks on the bottom right corner)
 - 上下文命令 (e.g. do the same with the blue block, undo that)
 - 基于语言的推理 (e.g. put the forest-colored block on the ocean-colored bowl)
 - 简单的问答 (e.g. how many blocks are to the left of the blue bowl?)