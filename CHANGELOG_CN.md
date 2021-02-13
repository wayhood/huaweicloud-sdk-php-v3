## 3.0.7-beta 2021-02-07
## HuaweiCloud SDK IMS
- ### 新增特性
    - 无
- ### 解决问题
    - 无
- ### 特性变更
    - 查询镜像支持的OS列表(ListOsVersions)接口返回体属性 `os_bit` 数据类型调整：string → int32


# 3.0.6-beta 2021-01-30
## HuaweiCloud SDK ECS
- ### 新增特性
    - 无
- ### 解决问题
    - 无
- ### 特性变更
    - 接口名称调整: UpdateAutoTerminateTimeServer → UpdateServerAutoTerminateTime

## HuaweiCloud SDK EVS
- ### 新增特性
    - 无
- ### 解决问题
    - 无
- ### 特性变更
    - 创建云硬盘接口支持指定专属存储池ID
    - 查询配额相关接口属性 `allocated` 类型调整: string → int

## HuaweiCloud SDK IAM
- ### 新增特性
    - 无
- ### 解决问题
    - 无
- ### 特性变更
    - 查询IAM用户详情接口响应体增加属性`access_mode`


# 3.0.5-beta 2021-01-25
## HuaweiCloud SDK Core
- ### 新增特性
    - 无
- ### 解决问题
    - 无
- ### 特性变更
    - 设置默认ConnectionTimeout为60秒
    - 设置默认ReadTimeout为120秒

## HuaweiCloud SDK ECS
- ### 新增特性
    - 新增支持接口：修改云服务器云主机销毁时间
- ### 解决问题
    - 无
- ### 特性变更
    - 无


# 3.0.4-beta 2021-01-15
## HuaweiCloud SDK Core
- ### 新增特性
    - 无
- ### 解决问题
    - 无
- ### 特性变更
    - 修改 `newBuilder` 函数


# 3.0.3-beta 2020-12-15
## HuaweiCloud SDK ECS
- ### 新增特性
    - 新增支持弹性云服务器
- ### 解决问题
    - 无
- ### 特性变更
    - 无

## HuaweiCloud SDK VPC
- ### 新增特性
    - 支持VPC v2版本的接口
- ### 解决问题
    - 无
- ### 特性变更
    - 无

## Huaweicloud SDK EIP
- ### 新增特性
    - 支持弹性公网IP服务
- ### 解决问题
    - 无
- ### 特性变更
    - 无


# 3.0.2-beta 2020-12-04
## HuaweiCloud SDK Core
- ### 新增特性
    - 无
- ### 解决问题
    - 解决从环境变量获取Credentials 时 HUAWEICLOUD_SDK_TYPE 变量没设置导致的 Credentials 类型错误问题。
- ### 特性变更
    - 增加侦听器功能来获取原始的为加密的Http请求和返回信息。

# 3.0.1-beta 2020-10-19
## 首次发布
- ### 已支持服务
    - 统一身份认证服务（IAM）