# Final task pool

Snapshot: 2026-10-24. Repository: `spallaselvylt934-alt/BenchTasksCollv3`.

This directory contains all **54 tasks marked implemented** in [Task Tracker](https://app.notion.com/p/Task-Tracker-40315df04e3881b18265e5e99a46e745), copied from the developer branch commits below. Each task is at `tasks/finalpool/<task-name>/`; all 268 source files and their relative layouts are preserved. Main and developer branches are unchanged.

## Review scope

The latest task batches on all 14 developer branches contain 29 named tasks and one unnamed entry under `tasks/yuxuan`. All 30 were added to the tracker as **implementing**: none has the required `task_config.json` committed. `currency-converter`, `insights-engine`, `audit-logger`, and `resource-monitor` also contain Chinese in documentation required to be English-only. None of these new entries is pooled.

Checks follow `tasks/examples/example-task`: required task and agent prompts must be non-empty and English-only; the optional user prompt must be English-only when non-empty; configuration must have non-empty `needed_mcp_servers` and `needed_local_tools` including `claim_done`. Optional evaluation/preprocess scripts and workspace folders are not blockers. No runtime or code-quality tests were imposed.

**Historical-status caveat:** the 54 existing implemented statuses were retained, not reclassified. Their source trees also lack `task_config.json`; they are included because they were already marked implemented in Notion, as requested. This pool is a faithful tracker-based collection, not a new certification that historical tasks pass the current template checks. No missing configuration or implementation was invented.

## Source snapshots

For each group, copy from the stated source prefix plus the task name to `tasks/finalpool/<task-name>/`.

### fan-dev (2 tasks)

- Source commit: `8b90f34538e4e106eba103265efaa9a456be498c`
- Source prefix: `tasks/fan/`
- Tasks: `coupon-manager`, `price-tracker`.

### gyy (4 tasks)

- Source commit: `9612ffff37072726292c77df0f4c6db2f8df1bbb`
- Source prefix: `tasks/gyy/`
- Tasks: `blog-engine`, `cms-builder`, `content-scheduler`, `social-publisher`.

### haoze (2 tasks)

- Source commit: `e0072cf979548c56984072cd76f529c7beea59b2`
- Source prefix: `tasks/haoze/`
- Tasks: `subtitle-generator`, `video-trimmer`.

### jl_dev (3 tasks)

- Source commit: `4e2b63f5dafce88b60886ed6e6af7bd9a8966296`
- Source prefix: `tasks/jl/`
- Tasks: `canvas-grade-automation`, `email-classification-system`, `pdf-report-generator`.

### junteng_dev (7 tasks)

- Source commit: `4ab0c5415824d799c3457a26482f9b794c7e9e93`
- Source prefix: `tasks/junteng/`
- Tasks: `booking-system`, `calendar-sync`, `contact-manager`, `order-processor`, `product-catalog`, `reminder-service`, `shipment-tracker`.

### junxian_dev (2 tasks)

- Source commit: `96bbc11b6fc701d07d961aaf070c434fccd1794f`
- Source prefix: `tasks/junxian/`
- Tasks: `qr-generator`, `translation-api`.

### lueyang-dev (6 tasks)

- Source commit: `bf8b9a1d25edd81b158db0bb7f49d8624348e74d`
- Source prefix: `tasks/lueyang/`
- Tasks: `activity-logger`, `crm-system`, `deal-manager`, `email-campaign`, `follow-up-reminder`, `sales-pipeline`.

### lv (5 tasks)

- Source commit: `0be3288e0fd4ae1f241d3ce9cc1c864ae2606d37`
- Source prefix: `tasks/lv/`
- Tasks: `chat-bot`, `feedback-collector`, `personalization-service`, `sentiment-analyzer`, `voice-processor`.

### ruige (4 tasks)

- Source commit: `a6f3fba387f68acaf6517803e88b40a4a3c52658`
- Source prefix: `tasks/ruige/`
- Tasks: `canvas-automation`, `data-analytics`, `expense-tracker`, `file-manager`.

### wenshuo-dev (2 tasks)

- Source commit: `d11080ed8d65fb72eb32d9353cb20844b593f9e8`
- Source prefix: `tasks/wenshuo/`
- Tasks: `image-processor`, `search-engine`.

### xiaochen_dev (5 tasks)

- Source commit: `20bfc73490dcf4029b92123b6055e076b7eb5dfa`
- Source prefix: `tasks/xiaochen/`
- Tasks: `backup-utility`, `deployment-tool`, `error-tracker`, `monitoring-agent`, `security-scanner`.

### yuxuan-dev (4 tasks)

- Source commit: `e82c8295f9506ced6862ab7f39048a731b48beb4`
- Source prefix: `tasks/yuxuan/`
- Tasks: `asset-optimizer`, `content-manager`, `network-analyzer`, `task-scheduler`.

### yuzhen-dev (6 tasks)

- Source commit: `c68265dafe0a0eccc6e183ff96d1a3e5591a3d8b`
- Source prefix: `tasks/yuzhen/`
- Tasks: `alert-system`, `data-validator`, `form-builder`, `invoice-generator`, `payment-processor`, `permission-manager`.

### zhaochen (2 tasks)

- Source commit: `b5f9cc4f79bb9218e40c0293ab9ec4e90352a626`
- Source prefix: `tasks/zhaochen/`
- Tasks: `load-balancer`, `template-engine`.

