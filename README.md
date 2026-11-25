# HBF 推理软硬件协同模拟工程

本项目研究固定等效算力、减少 HBM 栈后，HBF 对 LLM 推理首响、流式延迟、达标吞吐与成本的影响。工程包包含 Qwen3.8-27B FFN 微基准、256 请求回放、DeepSeek 八芯片研究、离线看板和论文资料。

在 [Releases](https://github.com/tohnee/hbf-inference-engineering/releases) 下载工程包和 SHA-256 校验文件。解压后打开 README.md，并通过 `python3 project.py verify` 校验包内文件。

报告区分公开硬件测量、模型推算和价格假设。
