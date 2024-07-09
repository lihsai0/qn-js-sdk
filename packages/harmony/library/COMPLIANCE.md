# SDK 使用合规说明

应国家法律法规及监管部门规章等的要求，App 开发运营者（以下简称“开发者”或“您”）在提供网络产品服务时应尊重和保护最终用户个人信息，不得违法违规收集使用个人信息，保证和承诺个人信息处理行为获得最终用户的授权同意，遵循最小必要原则，并且应当采取有效的技术措施和组织措施，确保个人信息安全。

为帮助开发者在满足个人信息安全保护相关的法律法规、政策和监管标准的前提下，合规地接入与使用我们的SDK（App的第三方SDK），避免出现侵害用户个人信息权益情形，上海七牛信息技术有限公司（以下简称“七牛”）特制定本 **SDK 合规说明文档** （以下简称“文档”）。

请您在接入、使用我们的SDK之前，请充分阅读和理解本文档内容。

## 一、App 个人信息保护的合规要求

为保护 App 最终用户的个人信息，App 及 App 的开发者需要满足如下合规要求：

* App 开发者应该制定隐私政策，并在 App 界面中显著展示。隐私政策（或命名为个人信息保护政策等类似名称），是说明 APP 的个人信息收集和使用情况，获得用户的合法授权以及保护用户个人信息主体权利的重要文档。可参考《GB/T 35273-2020 信息安全技术 个人信息安全规范》，该文件对个人信息保护要求和隐私政策编写具有重要的参考价值。
* App 隐私政策应该单独成文，而不是作为用户协议等文件中的一部分进行展示。
* App 隐私政策应该明示收集和使用个人信息的目的、方式和范围，并且确保隐私政策链接正常有效，易于访问和阅读。
* App 隐私政策应逐项说明 App 各项业务功能以及对应收集的个人信息类型，不应使用“等、例如”等方式概括说明。
* App 隐私政策应显著标识个人敏感信息类型（如：字体加粗等）。
* App 隐私政策应逐项说明调用的第三方 SDK，包括明示 SDK 名称、SDK 开发者名称；SDK 收集和处理的个人信息类型、目的、方式、范围；SDK 隐私政策链接。

## 二、SDK 合规声明

## SDK 所需权限声明

SDK 需要用户授权相应的权限后，方可正常运行，其所需权限列表如下：

### **上传 SDK**

基于 OpenHarmony 的平台所需应用权限列表：

|**权限**|**说明**|**可选性**|
|:----|:----|:----|
|FILE_ACCESS_MANAGER|用于读取用户选择的上传文件和写入日志|必须|
|REMOVE_CACHE_FILES|用于清理上传缓存文件|必须|
|INTERNET|用于联网上传文件至七牛云|必须|

### 隐私政策使用建议

App 首次运行时应当有隐私弹窗，隐私弹窗中应公示隐私政策内容并附完整隐私政策链接，并明确提示最终用户阅读并选择是否同意隐私政策；隐私弹窗应提供同意按钮和拒绝同意的按钮，并由最终用户主动选择。

App 取得敏感权限前，应通过隐私弹窗获得用户单独授权同意（如：麦克风权限、摄像头权限等）。

为满足法律法规和相关监管要求，您应确保在获得终端用户的同意后再初始化 SDK。如果最终用户不同意 App 隐私政策，则不能初始化视频 SDK，无法使用 SDK 功能。

## 三、联系方式

如第三方开发者和/或终端用户对本声明或个人信息相关事宜有疑问，可以通过以下方式与我们取得联系：

* [提交工单](https://support.qiniu.com/tickets/new)
* 通过七牛客服电话 400-808-9176转1
* 发送邮件至 [bd@qiniu.com](mailto:bd@qiniu.com)
* 邮寄信件至：中国上海市浦东新区浦东软件园Q座七牛云客服中心（收）邮编：201203
为保障我们高效处理您的问题并及时向您反馈，我们可能需要您提交身份证明、有效联系方式和书面请求及相关证据，我们将在验证请求人身份后尽快审核所涉问题，并于十五个工作日内予以回复。