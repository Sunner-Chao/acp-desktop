# ACP Desktop

基于 Tauri 2、React、TypeScript 和 Zustand 的 Agent Client Protocol（ACP）桌面客户端原型。协议实现和功能完整度以 `SPEC.md`、`src-tauri/` 与当前分支为准。

## 开发

要求 Node.js、Rust toolchain 和 Tauri 依赖：

    npm install
    npm run dev
    npm run build

桌面调试使用 `npx tauri dev`。桌面宿主可调用本地进程，运行未知 Agent 前审阅权限和工作目录。

## 目录

`src/` 前端、`src-tauri/` Rust/Tauri 宿主、`templates/` 模板、`scripts/` 辅助脚本、`SPEC.md` 约束说明。

## 当前状态与许可证

仓库未声明稳定发行版或完整 ACP 兼容矩阵。许可证以仓库 LICENSE（如有）和第三方组件许可证为准。

