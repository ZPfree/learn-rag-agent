https://research.google/blog/unlocking-dependable-responses-with-gemini-enterprise-agent-platforms-agentic-rag/?utm_source=twitter&utm_medium=social&utm_campaign=social_post&utm_content=gr-acct
其中步骤 1，对于复杂问题。Orchestrator 评估这不是一个一对一问题，把问题转给agent.2，planer 做出查询路径，3，重写查询，4，汇总。
它认为它和其他框架最大的区别是 查询没有得到足够的信息就会继续返回查询 直到完成，比如她在推理过程中会说明具体少了什么，Gap: "We are missing information from the source documents about allergic reactions or adverse events during the stay."
通过这种日志显示出不充分的信息，迭代回去继续查询，问题在于查询出来的答案 它是怎么知道少了哪部分的，planer 做出的目标吗？


## RAG流程
https://datawhalechina.github.io/all-in-rag
