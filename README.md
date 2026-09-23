# RAG‑Agent 智能客服系统
基于大模型 + RAG检索增强 + Agent智能体实现的对话客服系统

## ✨项目简介
本项目实现一个具备知识库检索能力的AI智能客服。
- 支持私有文档知识库向量检索（ChromaDB）
- 基于ReAct Agent实现工具调用、多轮推理
- Streamlit做Web可视化交互界面
- 可对接本地/云端大模型接口

## 📁目录结构
├─ agent/        # Agent智能体逻辑
├─ config/       # 配置文件
├─ prompts/      # 提示词模板
├─ rag/          # RAG检索模块
├─ utils/        # 工具函数
├─ app.py        # Streamlit入口主程序
└─ requirements.txt  # 依赖库

## 🚀快速运行
1. 安装依赖
```bash
pip install -r requirements.txt
2.配置.env填入模型API密钥
3.启动web服务
streamlit run app.py
🛠️技术栈
 
- Python 3.12
​
- LangChain
​
- ChromaDB向量数据库
​
- Streamlit
​
- 大模型API



