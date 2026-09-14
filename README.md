# MicroDuck 3D Model Recreation / MicroDuck 个人复刻模型

![MicroDuck standing CAD preview](images/microduck-standing.jpg)

这是一个由个人玩家 `laotawayer` 独立复刻和维护的 MicroDuck 3D 模型仓库，提供 SolidWorks 源文件与通用 STEP 导出文件。

This repository contains an independent hobbyist recreation of the MicroDuck 3D model, including SolidWorks source files and a STEP export.

## Preview / 模型预览

| Sitting pose / 坐姿 | Exploded view / 爆炸图 |
| --- | --- |
| ![MicroDuck sitting CAD preview](images/microduck-sitting.jpg) | ![MicroDuck exploded CAD view](images/microduck-exploded-view.jpg) |

## Physical Build / 实物照片

![MicroDuck physical build](images/microduck-physical-build.jpg)

实物照片用于展示当前装配状态；照片中的配色、线缆和装配细节可能与仓库中的 CAD 源文件存在差异。

The physical photo shows an assembled build in its current state. Colors, wiring, and assembly details in the photo may differ from the CAD source files.

## Repository Contents / 仓库内容

```text
cad/solidworks/        v0.1.0 SolidWorks source / v0.1.0 源文件
cad/solidworks-v0.2.0/ v0.2.0 SolidWorks source / v0.2.0 源文件
cad/solidworks-v0.2.1/ v0.2.1 SolidWorks source / v0.2.1 源文件
exports/step/          STEP exchange files / STEP 交换文件
images/           Preview renders / 模型预览图
CHANGELOG.md      Version history / 版本变更记录
DISCLAIMER.md     Legal and non-affiliation notice / 免责声明
LICENSE.md        Non-commercial license terms / 非盈利使用许可
VERSION           Current model version / 当前模型版本
models.sha256     Model integrity checksums / 模型校验值
STANDARD_PARTS.md Standard parts BOM / 标准件清单
FAQ.md            Frequently asked questions / 常见问题
ROADMAP.md        Project roadmap / 项目路线图
```

- Main assembly / 主要装配体：`cad/solidworks-v0.2.1/microduck.SLDASM`
- Full STEP export / 整机 STEP：`exports/step/v0.2.1/microduck-0914.STEP`
- Full SolidWorks source package / 完整 SolidWorks 源文件包：[v0.2.1 Release ZIP](https://github.com/laotawayer/microduck/releases/download/v0.2.1/microduck-v0.2.1-solidworks-source.zip)
- Current version / 当前版本：`0.2.1`
- CAD software / 建模软件：SolidWorks 2023（SW23）
- Units / 尺寸单位：毫米（mm）
- Manufacturing validation / 制造验证：已通过 / Passed

## v0.2.0 Changes / 第二版改动

- 修复部分模型干涉问题。
- 精简装配体包含的模型内容，删除不必要零件。
- 明确模型尺寸单位为毫米（mm）。
- 已完成制造验证。

- Fixed interference issues in several model areas.
- Simplified the assembly and removed unnecessary components.
- Confirmed millimetres (mm) as the model unit.
- Manufacturing validation passed.

## v0.2.1 Update / 更新

- 修复部分模型问题。
- 进一步精简源文件内容，由 49 个文件调整为 48 个文件。
- 保持毫米（mm）单位和已通过制造验证的状态。

## Reference Parts / 参考件

仓库中的轴承、紧固件、电路板、舵机或其他商品化部件模型可能仅用于装配定位和尺寸参考，其权利归各自权利人所有。

Bearings, fasteners, PCBs, servos, and other commercial components may be included solely as assembly references and remain subject to their respective owners' rights.

## Use and Safety / 使用与安全

在加工、打印或装配前，请自行核对尺寸、公差、材料、载荷、电气安全和运动干涉。本模型按现状提供，不构成制造、安全或特定用途保证。

Before fabrication, printing, or assembly, independently verify dimensions, tolerances, materials, loads, electrical safety, and mechanical interference. The files are provided as-is without a manufacturing, safety, or fitness guarantee.

> [!NOTE]
> GitHub's repository ZIP may show CAD files as small Git LFS pointer files. To download the actual SolidWorks files, use the complete source package in the Release link above.

## Download / 下载

| 内容 | 下载链接 |
| --- | --- |
| v0.2.1 SolidWorks 源文件完整压缩包（推荐） | [下载 v0.2.1 Release ZIP](https://github.com/laotawayer/microduck/releases/download/v0.2.1/microduck-v0.2.1-solidworks-source.zip) |
| v0.2.1 整机 STEP 文件 | [打开 microduck-0914.STEP](https://github.com/laotawayer/microduck/blob/main/exports/step/v0.2.1/microduck-0914.STEP) |
| v0.2.0 SolidWorks 源文件包 | [下载 v0.2.0 Release ZIP](https://github.com/laotawayer/microduck/releases/download/v0.2.0/microduck-v0.2.0-solidworks-source.zip) |
| v0.1.0 SolidWorks 源文件包 | [下载 v0.1.0 Release ZIP](https://github.com/laotawayer/microduck/releases/download/v0.1.0/microduck-v0.1.0-solidworks-source.zip) |
| 所有版本和下载统计 | [GitHub Releases](https://github.com/laotawayer/microduck/releases) |

推荐优先使用最新的 v0.2.1 Release ZIP；它包含真实 CAD 文件，适合一次性下载和统计下载量。

## Discussion / 评论区

模型问题、装配经验、版本转换和改进建议可在 [GitHub Discussions 评论区](https://github.com/laotawayer/microduck/discussions) 交流。涉及明确文件错误时，仍建议提交 Issue。

## Documentation / 文档

- [标准件型号与建议采购数量](STANDARD_PARTS.md)
- [SolidWorks 版本兼容与常见问题](FAQ.md)
- [项目路线图](ROADMAP.md)

## License / 许可

本仓库欢迎所有非盈利使用方式，包括个人学习、研究、教学、制造、打印、修改、二次创作、格式转换、展示和非盈利分享。个人二创无需另行申请授权。分享时需注明作者与仓库来源，并保留许可说明。

All non-commercial uses are welcome, including personal study, research, teaching, fabrication, printing, modification, derivative works, format conversion, display, and non-commercial sharing. Personal derivatives do not require separate permission. Attribution, a repository link where practical, and the license notice must be preserved when sharing.

未经作者事先书面授权，禁止盈利商用，也禁止将修改或二创后的成果用于盈利商用。包括销售文件或实物、收费打印加工、收费服务、广告赞助变现及商业产品使用。本许可并非 OSI 定义的开源许可证。

Profit-making commercial use of the original files or any derivative work is prohibited without the author's prior written permission. This includes sales, paid fabrication or services, monetized promotion, and commercial products. This is not an OSI-approved open-source license.

完整条款见 [LICENSE.md](LICENSE.md)，身份与第三方权利说明见 [DISCLAIMER.md](DISCLAIMER.md)。

See [LICENSE.md](LICENSE.md) for the binding terms and [DISCLAIMER.md](DISCLAIMER.md) for non-affiliation and third-party notices.

## Keywords

MicroDuck, robotics, robot design, CAD, SolidWorks 2023, STEP, 3D model, hobby robot, 机器人复刻, 三维模型, 舵机机器人
