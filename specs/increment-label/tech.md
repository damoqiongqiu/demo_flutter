# 计数器标签优化 — 技术 Spec

**关联**: specs/increment-label/product.md | **创建**: 2026-07-20

## 改动范围
- `lib/main.dart`: 两行 Text widget 文案调整
- `test/widget_test.dart`: 断言 find.text 匹配新格式

## 测试
- 原 widget_test 断言裸数字 → 改为 "0 times" / "1 times"
- flutter test + flutter analyze 全部通过
