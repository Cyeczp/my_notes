# 第四章 构建RAG应用



​		LangChain是一个用于构建基于大型语言模型（LLM）的应用程序的开源框架。它提供了一组工具和抽象，使开发人员可以轻松地将 LLM 集成到他们的应用程序中，并提高生成文本的质量和相关性。本文使用LangChain调用智谱GML。

​		向量数据库在第三章已完成构建。

构建检索问答链见代码task04.ipynb

​		在部署知识库助手中，教程所用模型为chatGPT，本文使用GML，见代码streamlit.py。在部署过程中遇到一个问题，
![image](https://github.com/Cyeczp/my_notes/blob/main/%E7%BB%84%E9%98%9F%E5%AD%A6%E4%B9%A0/2024-06llm/imgs/image-20240626180118692.png)



报错，添加”“成功解决。

![image](https://github.com/Cyeczp/my_notes/blob/main/%E7%BB%84%E9%98%9F%E5%AD%A6%E4%B9%A0/2024-06llm/imgs/image-20240626180216858.png)


![image](https://github.com/Cyeczp/my_notes/blob/main/%E7%BB%84%E9%98%9F%E5%AD%A6%E4%B9%A0/2024-06llm/imgs/image-20240626180245506.png)


