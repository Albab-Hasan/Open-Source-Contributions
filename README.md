# Open Source Contributions

All merged pull requests across open source projects.

**Total merged: 26**

---

## rust-lang/rust-analyzer (13 merged)

| PR | Title | Date |
|----|-------|------|
| [#22523](https://github.com/rust-lang/rust-analyzer/pull/22523) | fix: `extract_function` misses `&mut` for `container[i].mut_method()` | 2026-06-06 |
| [#22437](https://github.com/rust-lang/rust-analyzer/pull/22437) | fix: `extract_module` missing import for macro calls | 2026-05-25 |
| [#22077](https://github.com/rust-lang/rust-analyzer/pull/22077) | fix: avoid panic in replace_if_let_with_match on jump scrutinee | 2026-04-17 |
| [#22073](https://github.com/rust-lang/rust-analyzer/pull/22073) | fix: handle empty `/**/` in block_to_line assist | 2026-04-17 |
| [#22020](https://github.com/rust-lang/rust-analyzer/pull/22020) | internal: migrate `inline_call` assist to `SyntaxEditor` | 2026-04-12 |
| [#21838](https://github.com/rust-lang/rust-analyzer/pull/21838) | fix: skip usages inside macro expansions in destructure struct/tuple binding | 2026-03-18 |
| [#21794](https://github.com/rust-lang/rust-analyzer/pull/21794) | fix: add naming convention validation for `union` types | 2026-03-10 |
| [#21779](https://github.com/rust-lang/rust-analyzer/pull/21779) | fix: replace TODO placeholders in next-solver IrPrint with proper formatting | 2026-03-07 |
| [#21726](https://github.com/rust-lang/rust-analyzer/pull/21726) | fix: align `is_rust()` with rustc by correcting constructor ABI in next solver | 2026-03-01 |
| [#21699](https://github.com/rust-lang/rust-analyzer/pull/21699) | fix: Detect E0804 when casting raw ptr-to-dyn adds auto traits | 2026-02-24 |
| [#21654](https://github.com/rust-lang/rust-analyzer/pull/21654) | fix: use `ExprIsRead::Yes` for rhs of binary operators | 2026-02-16 |
| [#21649](https://github.com/rust-lang/rust-analyzer/pull/21649) | fix: use `ExprIsRead::Yes` for rhs of ordinary assignments | 2026-02-15 |
| [#21647](https://github.com/rust-lang/rust-analyzer/pull/21647) | fix: handle `ref mut` bindings in `contains_explicit_ref_binding` | 2026-02-14 |

---

## zed-industries/zed (7 merged)

| PR | Title | Date |
|----|-------|------|
| [#54878](https://github.com/zed-industries/zed/pull/54878) | gpui_wgpu: Respect `buffer_font_fallbacks` setting | 2026-04-25 |
| [#50173](https://github.com/zed-industries/zed/pull/50173) | gpui: Fix `send_file_drop_event` holding mutex during event callback | 2026-02-26 |
| [#49906](https://github.com/zed-industries/zed/pull/49906) | gpui: Call `ack_configure` on throttled Wayland resize events | 2026-02-23 |
| [#49022](https://github.com/zed-industries/zed/pull/49022) | gpui: Fix Core Foundation object leaks on macOS | 2026-02-12 |
| [#48850](https://github.com/zed-industries/zed/pull/48850) | gpui: Fix double-close of fd in read_fd on linux | 2026-02-10 |
| [#48727](https://github.com/zed-industries/zed/pull/48727) | gpui: Reset `external_files_dragged` after successful drag-drop on macOS | 2026-02-08 |
| [#48317](https://github.com/zed-industries/zed/pull/48317) | agent: Remove duplicate `line_hint` assignment in `StreamingFuzzyMatcher::push` | 2026-02-04 |

---

## ace-step/ACE-Step-1.5 (4 merged)

| PR | Title | Date |
|----|-------|------|
| [#343](https://github.com/ace-step/ACE-Step-1.5/pull/343) | fix: path traversal vulnerability in audio file path parameters | 2026-02-08 |
| [#319](https://github.com/ace-step/ACE-Step-1.5/pull/319) | fix: prevent arbitrary code execution via unsafe torch.load() | 2026-02-08 |
| [#226](https://github.com/ace-step/ACE-Step-1.5/pull/226) | fix: use per-socket timeout instead of global setdefaulttimeout | 2026-02-06 |
| [#161](https://github.com/ace-step/ACE-Step-1.5/pull/161) | fix: path traversal vulnerability in audio endpoint | 2026-02-05 |

---

## rust-lang/rust (2 merged)

| PR | Title | Date |
|----|-------|------|
| [#157413](https://github.com/rust-lang/rust/pull/157413) | fix: don't suggest .into_iter() for .cloned()/.copied() on non-reference Option | 2026-06-08 |
| [#153469](https://github.com/rust-lang/rust/pull/153469) | docs: clarify path search behavior in std::process::Command::new | 2026-03-06 |
