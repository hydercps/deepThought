# deepThought
一个聊天机器人

>  The answer to life, universe and everything is 42   --deepThought

# 目标
*  具有从真实对话或语料库中学习的能力
 *  有泛化能力
*  能从自然语言中推测用户意图
*  针对意图，给予恰当回答（回调任务模块）
*  构造通用的解析工具，将自然语言解析为结构化信息

# 核心概念
*  意图（intent）
*  实体
*  结构化的实体输出
  *  实体的模式  
  *  引导补齐


# 设计
*  插件化
  *  输入/输出
  *  存储
  *  逻辑单元
*  事件驱动（意图）
*  让数据在管道中流动

# 涉及知识
*  自然语言处理（NLP）
  *  中文分词
  *  命名实体识别
*  正则表达式
*  机器学习
  *  朴素贝叶斯


# todo
*  将wit作为bot的一个logic adapter
 *  添加timeout 
