# user_receipt_data 用户小票数据
---------------------------

<br />
### online interface:
<br />

###### addAddrCallerAllowed(string)
* 接口描述: 添加允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### addConCallerAllowed(string)
* 接口描述: 添加允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### delAddrCallerAllowed(string)
* 接口描述: 删除允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### delConCallerAllowed(string)
* 接口描述: 删除允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### checkinUserReceiptHash(string)	
* 接口描述: 提交用户小票数据hash
* 接口参数: 小票数据hash|备注信息
* 接口调用者: 拥有本合约操作权限的用户或合约

###### abolishUserReceiptHash(string)
* 接口描述: 撤销用户小票数据hash
* 接口参数: 小票数据hash
* 接口调用者: 拥有本合约操作权限的用户或合约

<br />
### offline interface:
<br />

###### verifyUserReceiptHash(string)
* 接口描述: 校验用户小票数据hash是否在链上
* 接口参数: 小票数据hash
* 接口调用者: 任意用户

###### getContractName()
* 接口描述: 获取合约名
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedAddrCaller()
* 接口描述: 获取允许操作本合约的用户地址
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedConCaller()
* 接口描述: 获取允许操作本合约的合约地址
* 接口参数: 无
* 接口调用者: 任意用户

<br />
<br />
<br />
<br />

# mining_result_data 挖矿结果数据
---------------------------

<br />
### online interface:
<br />

###### addAddrCallerAllowed
* 接口描述: 添加允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### addConCallerAllowed
* 接口描述: 添加允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### delAddrCallerAllowed
* 接口描述: 删除允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### delConCallerAllowed
* 接口描述: 删除允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### checkinMiningResultHash	
* 接口描述: 提交挖矿结果数据hash
* 接口参数: 挖矿结果数据hash|备注信息
* 接口调用者: 拥有本合约操作权限的用户或合约

###### abolishMiningResultHash
* 接口描述: 撤销挖矿结果数据hash
* 接口参数: 挖矿结果数据hash
* 接口调用者: 拥有本合约操作权限的用户或合约

<br />
### offline interface:
<br />

###### verifyMiningResultHash
* 接口描述: 校验挖矿结果数据hash是否在链上
* 接口参数: 挖矿结果数据hash
* 接口调用者: 任意用户

###### getContractName
* 接口描述: 获取合约名
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedAddrCaller
* 接口描述: 获取允许操作本合约的用户地址
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedConCaller
* 接口描述: 获取允许操作本合约的合约地址
* 接口参数: 无
* 接口调用者: 任意用户

<br />
<br />
<br />
<br />

# ad_putting_feedback_data 广告投放反馈数据
---------------------------

<br />
### online interface:
<br />

###### addAddrCallerAllowed
* 接口描述: 添加允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### addConCallerAllowed
* 接口描述: 添加允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### delAddrCallerAllowed
* 接口描述: 删除允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### delConCallerAllowed
* 接口描述: 删除允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### checkinAdPuttingFeedbackHash
* 接口描述: 提交广告投放反馈数据hash
* 接口参数: 广告投放反馈数据hash|备注信息
* 接口调用者: 拥有本合约操作权限的用户或合约
	
###### abolishAdPuttingFeedbackHash
* 接口描述: 撤销广告投放反馈数据hash
* 接口参数: 广告投放反馈数据hash
* 接口调用者: 拥有本合约操作权限的用户或合约

<br />
### offline interface:
<br />

###### verifyAdPuttingFeedbackHash
* 接口描述: 校验广告投放反馈数据hash是否在链上
* 接口参数: 广告投放反馈数据hash
* 接口调用者: 任意用户

###### getContractName
* 接口描述: 获取合约名
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedAddrCaller
* 接口描述: 获取允许操作本合约的用户地址
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedConCaller
* 接口描述: 获取允许操作本合约的合约地址
* 接口参数: 无
* 接口调用者: 任意用户

<br />
<br />
<br />
<br />

# ad_putting_result_data 广告投放反馈统计结果数据
---------------------------

<br />
### online interface:
<br />

###### addAddrCallerAllowed
* 接口描述: 添加允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### addConCallerAllowed
* 接口描述: 添加允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### delAddrCallerAllowed
* 接口描述: 删除允许操作本合约的用户地址
* 接口参数: 用户地址
* 接口调用者: 数据管理员

###### addConCallerAllowed
* 接口描述: 删除允许操作本合约的合约地址
* 接口参数: 合约地址
* 接口调用者: 数据管理员

###### checkinAdPuttingResultHash	
* 接口描述: 提交广告投放反馈统计结果数据hash
* 接口参数: 广告投放反馈统计结果数据hash|备注信息
* 接口调用者: 拥有本合约操作权限的用户或合约

###### abolishAdPuttingResultHash
* 接口描述: 撤销广告投放反馈统计结果数据hash
* 接口参数: 广告投放反馈统计结果数据hash
* 接口调用者: 拥有本合约操作权限的用户或合约

<br />
### offline interface:
<br />

###### verifyAdPuttingResultHash
* 接口描述: 校验广告投放反馈统计结果数据hash是否在链上
* 接口参数: 广告投放反馈统计结果数据hash
* 接口调用者: 任意用户

###### getContractName
* 接口描述: 获取合约名
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedAddrCaller
* 接口描述: 获取允许操作本合约的用户地址
* 接口参数: 无
* 接口调用者: 任意用户

###### getallowedConCaller
* 接口描述: 获取允许操作本合约的合约地址
* 接口参数: 无
* 接口调用者: 任意用户


