# Joel 的大唠嗑的预览服务
当 [Joel 的大唠嗑](https://github.com/iamjoel/dialogue) 仓库的内容变化时，这边会去同步内容，并构建。

原因是：`Joel 的大唠嗑` 内容的预览是用的 [`quartz`](https://quartz.jzhao.xyz/) 做的。但是，`quartz` 的源码和用户的内容(Joel 的大唠嗑)是混在一起的，导致多了额外内容。为解决这个问题，就把内容和预览服务放在了两个仓库。内容仓库变动时，触发构建预览服务仓库的同步和构建预览服务的功能。

