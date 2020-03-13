# BankCardInfo

通过银行卡号返回银行名称、银行缩写code、银行卡类型


## 安装：
```
gem install bank_card_info

gem 'bank_card_info'
```


## 返回银行卡号信息:

```
BankCardInfo.bank_card_info("6214680014567106")

结果:

{:bank_name=>"北京银行", :bank_code=>"BJBANK", :card_number=>"6214680014567106", :card_type=>"DC", :card_type_name=>"储蓄卡"}
```

## 返回支持的银行卡信息：

```
BankCardInfo.banks
```

# 最重要的： 请右上角给我一颗星