# git workflow guide

## 前言
  在目前我们team的研发工作中，都是用一个分支来开发、测试、发布、发布hotfix.  
  但是实际情况是，team内部不同的人在开发不同的需求，本来只想发布上线其中的一个或者部分需求，但是在只有一个分支的情况下很难分开这些代码，另外hotfix和feature的代码也是合在一起的，只是想发布hotfix的时候，feature的代码也很难分开。
  所以我们需要将git的工作流规范化，并特此定义了git的工作流程指南。  
  
  * 1.[工作流与规范](01.0.md)