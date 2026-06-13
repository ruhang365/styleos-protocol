# Face Shape Tags

Face-shape tags are auxiliary styling signals. They should not be used as identity labels, attractiveness labels, or body judgment.

中文说明：
脸型标签只是辅助判断，不应该作为用户身份标签，不应该用于外貌评价。真实服务中应结合发量、发质、五官量感、场景、目标和维护意愿综合判断。

## Tag Format

Each starter tag includes definition, visual signals, common styling goals, caution, and identity boundary.

## v0.2 Usage Notes

- Treat face-shape tags as one signal among hair volume, hair texture, goal, scenario, and maintenance willingness.
- Prefer combined signals such as `face_shape_square + goal_balance_jawline + maintenance_low` instead of a single-label conclusion.
- When input is partial or angle-dependent, use `face_shape_mixed_uncertain` and output a lower-risk barber brief.
- Do not rank faces or describe a face shape as a flaw. The tag only helps choose length, layering, parting, and volume direction.
- For creator output, pair face tags with [Face Proportion Tags](./face-proportion-tags.md) and [Jawline / Cheekbone / Forehead Tags](./jawline-cheekbone-forehead-tags.md).

## `face_shape_oval`

- Definition: 轮廓比例相对均衡，脸部长度和宽度没有明显单点突出。
- Visual signals: 额头、颧部、下颌过渡较自然，整体轮廓较连续。
- Common styling goals: 保持平衡、强化个人风格、提升清爽度。
- Caution: 不代表所有发型都适合；仍需结合发量、发质和场景。
- Not a fixed identity: 这只是当前视觉信号，不是固定身份标签。

## `face_shape_round`

- Definition: 面部宽度和柔和曲线感相对明显。
- Visual signals: 轮廓转折较少，脸颊区域视觉存在感较高。
- Common styling goals: 增加清爽度、拉开面部纵向比例、减少两侧堆积感。
- Caution: 不应使用“显胖”等羞辱性语言。
- Not a fixed identity: 只用于判断发型轮廓策略，不定义用户本人。

## `face_shape_square`

- Definition: 下颌或面部外轮廓线条感较明显。
- Visual signals: 下颌宽度、下颌角或面部下半部分结构感较强。
- Common styling goals: 柔化下颌存在感、避免长度正好卡在最宽处、提升亲和感。
- Caution: 不应把线条感描述为缺点；它也可以支持成熟、利落、专业感。
- Not a fixed identity: 只描述视觉线条倾向。

## `face_shape_long`

- Definition: 纵向比例相对更明显。
- Visual signals: 面部长度感强于宽度感，额头、面中或下巴任一区域可能拉长视觉。
- Common styling goals: 降低过度纵向拉伸、增加横向柔和层次、控制头顶高度。
- Caution: 不要把长脸等同于年龄、性格或气质判断。
- Not a fixed identity: 只作为发型比例参考。

## `face_shape_heart`

- Definition: 上半脸或额头视觉存在感较强，下颌或下巴相对收窄。
- Visual signals: 额头或颧部更突出，下巴线条更集中。
- Common styling goals: 平衡额头、增加下半脸柔和度、避免上方重量过强。
- Caution: 不要机械套用厚刘海遮挡。
- Not a fixed identity: 只是一个初始轮廓倾向。

## `face_shape_diamond`

- Definition: 颧部视觉存在感较强，额头和下颌相对收窄。
- Visual signals: 中面部宽度或颧骨线条更明显。
- Common styling goals: 柔化颧部边界、平衡上下比例、避免侧面过度蓬宽。
- Caution: 不应把颧部存在感当成负面描述。
- Not a fixed identity: 只用于造型策略判断。

## `face_shape_pear_triangle`

- Definition: 下半脸或下颌视觉重量相对更明显。
- Visual signals: 下颌宽度或下半脸存在感强于额头区域。
- Common styling goals: 增加上方轻盈体积、平衡下颌、避免下颌处堆积。
- Caution: 不应引导医学或外科改变建议。
- Not a fixed identity: 只是可变的视觉比例信号。

## `face_shape_mixed_uncertain`

- Definition: 输入不足、照片角度影响大，或多种轮廓信号混合。
- Visual signals: 不同角度判断差异明显，或创作者无法稳定归类。
- Common styling goals: 先输出低风险、可调整的发型策略。
- Caution: 应明确不确定性，不要强行分类。
- Not a fixed identity: 不确定就是有效结论，不能为了交付而制造确定性。
