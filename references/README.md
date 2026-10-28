# 2027考研英语二三份高频词资料

这份目录登记2026-10-28上传到ChatGPT对话的三份扫描版PDF。原件**尚未通过GitHub连接器上传**，不要将目录登记误认为文件已在仓库内。

- **HF2000**：十天背完！2000个高频词，10页，编号1–2000。两轮基础词表。
- **EXAM27**：27考研英语历年真题高频词汇，11页。以资料标注的出现次数作为额外优先级。
- **READ200**：英语阅读真题高频200词（标注了词频），51页。优先学高频释义、语境、熟词僻义和派生词。

原文件名、SHA256、计划存放路径和上传状态见 [data/vocabulary_sources.json](../data/vocabulary_sources.json)。需要将原件手动上传至本目录后将状态标记为已验证，并再建立可查询词库。资料可能有重叠，不允许将同一词重复计入两轮目标。相关计划在 [data/vocabulary_plan.json](../data/vocabulary_plan.json)。

## PDF原件上传步骤

GitHub浏览器一次上传单个文件不得超过25 MiB。源PDF已在ChatGPT会话中，GitHub连接器目前未能直接传输二进制附件。

1. 打开此目录（references），点击 Add file → Upload files。
2. 上传两份小于25 MiB的原文件：`1考研高频词汇总【2000词】.pdf`、`27考研英语历年真题高频词汇-.pdf`。
3. 第三份51页阅读PDF原件约32.5 MB，浏览器超限。可从本次对话下载重新采样压缩的`阅读高频200词_适合GitHub上传.pdf`（12,760,906字节，SHA256 eac463656794fe0c6022c86c01ceb54be891214dd7fccf954d620a086bfd5b61），然后上传。
4. 点击 Commit changes。上传后核对各文件路径和SHA256，更新`data/vocabulary_sources.json`中的`pdf_uploaded_to_github`，才可标记原件已归档。

来源还包含词汇索引：`data/wordlists/reading200_page_index.json`已有初步202个页首词条，`data/wordlists/other_source_seeds.json`只有高频2000第一栏54词和另一份资料8个高频样本，尚未完成全量核录。
注意：仓库当前公开。若没有相关资料的公开传播授权，建议改成私有仓库后再上传PDF。
