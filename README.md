# 本地影院 · LocalCinema 隐私政策

这个仓库只有一个用途：给 Chrome 应用商店提供一个公开可访问的隐私政策地址。

- 隐私政策页面：<https://zxingwork.github.io/localcinema-privacy/privacy.html>
- 根地址（自动跳转）：<https://zxingwork.github.io/localcinema-privacy/>

> **发布分支是 `gh-pages`。** GitHub 认这个分支名自动发布 Pages；`main` 只是同一份内容的镜像，
> 方便在仓库首页直接看到最新内容，**改动请推 `gh-pages`**（或在应用仓库里跑 `node store/publish-privacy.mjs`）。

政策正文的源文件在应用仓库的 `privacy.html` / `store/privacy.md`，改完后跑一次：

```powershell
node store/publish-privacy.mjs
```

## 一句话内容

本地影院把整个应用跑在用户自己的浏览器里：**没有任何网络请求，不收集、不存储、不传输任何数据**，扩展也不申请任何浏览器权限。
