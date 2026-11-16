# DanceSense · App Store 页面

DanceSense（舞蹈标准度测试）的静态页面，托管在 GitHub Pages 上，供 App Store Connect 填写。

| 文件 | 用途 | 填到 ASC 的位置 |
|---|---|---|
| `index.html` | 落地页（避免根地址 404，给出两个入口） | 不用填 |
| `support.html` | 技术支持页 | App 信息 → 一般信息 → **支持 URL** |
| `privacy.html` | 隐私政策页（中英双语） | App 隐私 → **隐私政策 URL** |

发布后的地址形如：

```
https://thoexxr.github.io/DanceSense-site/
https://thoexxr.github.io/DanceSense-site/support.html
https://thoexxr.github.io/DanceSense-site/privacy.html
```

## 更新方式

改完本地 `privacy-site/` 下的文件，直接覆盖上传（Add file → Upload files）或 `git push` 即可，
Pages 会在 1–2 分钟内重新构建。

## 注意事项

- 仓库必须是 **public**，否则 Pages 不能公开访问，ASC 校验会失败。
- 支持 URL / 隐私 URL 提交审核后不要删除仓库或改动文件路径。
- 联系邮箱：`xingran0720@gmail.com`。
- 页面语言：隐私页与支持页均为中英双语（与 App 内 7 种语言不强绑定；如需按语言分包，可后续加 `/ja/`、`/ko/` 等目录）。
