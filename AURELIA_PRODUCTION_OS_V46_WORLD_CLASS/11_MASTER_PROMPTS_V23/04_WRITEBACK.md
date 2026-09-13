# V23 WRITEBACK

写回不是“把文本覆盖回文件”。

流程：读取目标 revision → 生成 typed patch → 分类变化 → authority check → validate → transaction prepare → apply → verify → commit → audit → acknowledge。

revision 不匹配、语义冲突、证据不足或授权不足时不得提交。
