---
layout: popup
---

- File: `op3_walking_module_msgs/SetWalkingParam.srv`

- Message Definition
 ```
 WalkingParam        parameters
 ---
 bool                result
 ```

- Description
This service configures parameters in `op3_walking_module` for walking control.  

  - Request  
* `WalkingParam parameters`([op3_walking_module_msgs/WalkingParam])   
&emsp;&emsp; Walking paramters to be applied on `op3_walking_module`. For details, refer to [WalkingParam.msg].

  - Response
* `bool result`   
&emsp;&emsp;


[op3_walking_module_msgs/WalkingParam]: /docs/en/popup/op3_WalkingParam.msg/
[WalkingParam.msg]: /docs/en/popup/op3_WalkingParam.msg/