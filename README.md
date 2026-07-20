# demo_flutter

**这是一个测试项目，用于验证 [my-harness-flow](https://github.com/damoqiongqiu/my-harness-flow) 框架的 mobile profile，没有任何实际业务功能。**

## 验证项

- harness install `--profile mobile` ✅
- L1 移动端健康检查（SDK / 模拟器 / 文件完整性） 6/6 ✅
- flutter analyze — No issues ✅
- flutter test — 1/1 ✅
- L2 集成测试定义就绪

## 运行

```bash
flutter run                     # 启动应用
flutter test                    # 单元测试
flutter analyze                 # 静态分析
bash l1-health-check.sh         # harness L1 冒烟
bash l2-integration.sh          # harness L2 单元
```
