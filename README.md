# runharbor-hello

A one-job smoke test for [RunHarbor](https://runharbor.poset.dev): the job runs on an ephemeral EC2 runner in your own AWS account.

1. Create your copy with **Use this template** (a private repository is fine).
2. It runs once on the first commit. To run it again: **Actions → hello → Run workflow**.
3. If your RunHarbor GitHub App was installed on *selected* repositories only, add this repository to the App first; otherwise the job waits in the queue.

---

RunHarbor 冒烟测试：这个 job 会在你自己 AWS 账号里临时启动的 EC2 runner 上运行，跑完即销毁。

1. 点 **Use this template** 创建你自己的副本（可以设为私有）。
2. 首次提交会自动跑一次；再次运行：**Actions → hello → Run workflow**。
3. 如果安装 RunHarbor 的 GitHub App 时只选了部分仓库，请先把这个仓库加进去，否则 job 会一直排队。
