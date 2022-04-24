# GetinfoResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**netid** | **String** | 网络版本号 |  [optional]
**totalAmount** | **Long** | 发行总量 |  [optional]
**balance** | **Long** | 可用余额 |  [optional]
**balanceFrozen** | **Long** | 冻结的余额 |  [optional]
**balanceLockup** | **Long** | 锁仓的余额 |  [optional]
**testnet** | **Boolean** | 是否是测试网络 |  [optional]
**blocks** | **Long** | 已经同步到的区块高度 |  [optional]
**group** | **Long** | 区块组高度 |  [optional]
**startingBlock** | **Long** | 区块开始高度 |  [optional]
**startBlockTime** | **Long** | 创始区块出块时间 |  [optional]
**highestBlock** | **Long** | 所链接的节点的最高高度 |  [optional]
**currentBlock** | **Long** | 已经同步到的区块高度 |  [optional]
**pulledStates** | **Long** | 正在同步的区块高度 |  [optional]
**blockTime** | **Long** | 出块时间 |  [optional]
**lightNode** | **Long** | 轻节点押金数量 |  [optional]
**communityNode** | **Long** | 社区节点押金数量 |  [optional]
**witnessNode** | **Long** | 见证人押金数量 |  [optional]
**nameDepositMin** | **Long** | 域名押金最少金额 |  [optional]
**addrPre** | **String** | 地址前缀 |  [optional]
**tokenBalance** | [**List&lt;TokenBalance&gt;**](TokenBalance.md) | token余额收益 |  [optional]
