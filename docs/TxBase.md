# TxBase

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hash** | **byte[]** | 交易hash |  [optional]
**type** | **Long** | 交易类型 |  [optional]
**vinTotal** | **Long** | 输入交易数量 |  [optional]
**vin** | [**Vin**](Vin.md) |  |  [optional]
**voutTotal** | **Long** | 输出交易数量 |  [optional]
**vout** | [**Vout**](Vout.md) |  |  [optional]
**gas** | **Long** | 交易手续费 |  [optional]
**lockHeight** | **Long** | 本交易锁定在小于等于这个高度的块中，超过这个高度，块将不被打包到区块中。 |  [optional]
**payload** | **byte[]** | 备注信息 |  [optional]
**blockHash** | **byte[]** | 本交易属于的区块hash，不参与区块hash，只用来保存 |  [optional]
