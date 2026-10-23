# 吉隆灾害链建模研究：下载文件

请在 GitHub 网页登录具有本仓库访问权限的账户后，点击下表中的下载链接。下载使用普通 HTTPS 链接，不依赖聊天页面的云端文件连接。

| 文件 | 内容 | 下载 |
|---|---|---|
| Word 论文 | 66页；100条编号公式；原生可编辑公式 | [下载 Word](./paper.docx?raw=true) |
| PDF 论文 | 最终阅读与打印版本 | [下载 PDF](./paper.pdf?raw=true) |
| 代码与建模方案 | 完整 Python 代码及完整推导源稿 | [下载代码方案包](./code_and_methods.zip?raw=true) |
| 全部研究成果 | 论文、代码、计算结果、17张独立TIFF/EPS图件、字体与运行说明；不含原始附件 | [下载成果包](./research_outputs.zip?raw=true) |

如点击链接后进入文件页，使用 GitHub 文件页的 Download raw file（下载原始文件）按钮。大型成果包约91.5 MiB。

## 解释与复现边界

- 本分支仅用于交付，不改动主分支。原始数据附件未上传至仓库。
- 最终产物包含17张独立图件、15张三线表；TIFF为600 dpi透明RGBA，EPS不支持alpha通道。
- 当前用户确认使用思源宋体；代码包含授权宋体的一键切换脚本。
- 缺少独立灾害发生时间，真实泥石流触发时间95%区间与业务覆盖率尚不能验证；气温代理与仿真情景不等于实灾预报。
- 第（3）RAR未读取，外部遥感和气象数据下载受代理限制；具体状态在论文和结果记录中明确列出。
- 完整复算需要用户原始附件，安装依赖并遵照README运行。

## 校验和

```text
de2c59fc4bb25c2502492d72338b6f004e1079c988e9d5fd115a36d654f76ffc  paper.docx
d6697e7d105e5a16399a5e3a8e30354e9711a3623a693f83d23d1e3764e49a9e  paper.pdf
ba52d0e997fca7d84dab78c8d6f9d69c3f59f2243f64f5b16fcb4e4e3dd00af2  code_and_methods.zip
618e89bab64137f8d94083b325a468ef0bc23edd8e9d95910f71c00e1c2730f8  research_outputs.zip
```
