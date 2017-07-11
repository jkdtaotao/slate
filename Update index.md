--- 

title: wetechplatform API 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

wetechplatform API documentation 

**Version:** 0.0.1 

# /API/_SEARCH/USERS
## ***GET*** 

**Summary:** search

### HTTP Request 
`***GET*** /api/_search/users` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-ACCOUNT-FEATURES
## ***GET*** 

**Summary:** searchWtAccountFeatures

### HTTP Request 
`***GET*** /api/_search/wt-account-features` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-ACCOUNTS
## ***GET*** 

**Summary:** searchWtAccounts

### HTTP Request 
`***GET*** /api/_search/wt-accounts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-EMAIL-TEMPLATES
## ***GET*** 

**Summary:** searchWtEmailTemplate

### HTTP Request 
`***GET*** /api/_search/wt-email-templates` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-EMAILS
## ***GET*** 

**Summary:** searchWtEmails

### HTTP Request 
`***GET*** /api/_search/wt-emails` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-MERCHANTS
## ***GET*** 

**Summary:** searchWtMerchants

### HTTP Request 
`***GET*** /api/_search/wt-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-SETTLEMENT-LOGS
## ***GET*** 

**Summary:** searchWtSettlementLogs

### HTTP Request 
`***GET*** /api/_search/wt-settlement-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | No | string |
| queryDateField | query | queryDateField | No | string |
| queryDateFieldFrom | query | queryDateFieldFrom | No | string |
| queryDateFieldTo | query | queryDateFieldTo | No | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-TRANSACTION-CURRENCIES
## ***GET*** 

**Summary:** searchWtTransactionCurrencies

### HTTP Request 
`***GET*** /api/_search/wt-transaction-currencies` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-TRANSACTION-ERROR-LOGS
## ***GET*** 

**Summary:** searchWtTransactionErrorLogs

### HTTP Request 
`***GET*** /api/_search/wt-transaction-error-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-TRANSACTION-JOURNALS
## ***GET*** 

**Summary:** searchWtTransactionJournals

### HTTP Request 
`***GET*** /api/_search/wt-transaction-journals` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-TRANSACTIONS
## ***GET*** 

**Summary:** pageable

### HTTP Request 
`***GET*** /api/_search/wt-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | No | string |
| queryDateField | query | queryDateField | No | string |
| queryDateFieldFrom | query | queryDateFieldFrom | No | string |
| queryDateFieldTo | query | queryDateFieldTo | No | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-USER-MERCHANTS
## ***GET*** 

**Summary:** searchWtUserMerchants

### HTTP Request 
`***GET*** /api/_search/wt-user-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-WX-MERCHANT-CONFIGS
## ***GET*** 

**Summary:** searchWtWxMerchantConfigs

### HTTP Request 
`***GET*** /api/_search/wt-wx-merchant-configs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/_SEARCH/WT-WX-TRANSACTIONS
## ***GET*** 

**Summary:** searchWtWxTransactions

### HTTP Request 
`***GET*** /api/_search/wt-wx-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| query | query | query | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/ACCOUNT
## ***GET*** 

**Summary:** getAccount

### HTTP Request 
`***GET*** /api/account` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** saveAccount

### HTTP Request 
`***POST*** /api/account` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| userDTO | body | userDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/ACCOUNT/CHANGE_PASSWORD
## ***POST*** 

**Summary:** changePassword

### HTTP Request 
`***POST*** /api/account/change_password` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| password | body | password | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/ACCOUNT/RESET_PASSWORD/FINISH
## ***GET*** 

**Summary:** verifyResetPasswordKey

### HTTP Request 
`***GET*** /api/account/reset_password/finish` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| key | query | key | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** finishPasswordReset

### HTTP Request 
`***POST*** /api/account/reset_password/finish` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| keyAndPassword | body | keyAndPassword | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/ACCOUNT/RESET_PASSWORD/INIT
## ***POST*** 

**Summary:** requestPasswordReset

### HTTP Request 
`***POST*** /api/account/reset_password/init` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| mail | body | mail | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/ACTIVATE
## ***GET*** 

**Summary:** activateAccount

### HTTP Request 
`***GET*** /api/activate` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| key | query | key | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/APPLICATION/MERCHANT/DEFAULT-ACCOUNT
## ***PUT*** 

**Summary:** merchantSetDefaultAccount

### HTTP Request 
`***PUT*** /api/application/merchant/default-account` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| merchantBODeprecated | body | merchantBODeprecated | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/APPLICATION/MERCHANTS
## ***PUT*** 

**Summary:** merchantUpdate

### HTTP Request 
`***PUT*** /api/application/merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| merchantBODeprecated | body | merchantBODeprecated | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/APPLICATION/MERCHANTS/SIGNUP
## ***POST*** 

**Summary:** merchantSignUp

### HTTP Request 
`***POST*** /api/application/merchants/signup` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| merchantBODeprecated | body | merchantBODeprecated | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/AUTHENTICATE
## ***GET*** 

**Summary:** isAuthenticated

### HTTP Request 
`***GET*** /api/authenticate` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** authorize

### HTTP Request 
`***POST*** /api/authenticate` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| loginVM | body | loginVM | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/ELASTICSEARCH/INDEX
## ***POST*** 

**Summary:** reindexAll

### HTTP Request 
`***POST*** /api/elasticsearch/index` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/INVITE
## ***GET*** 

**Summary:** getInvitationInfo

### HTTP Request 
`***GET*** /api/invite` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| key | query | key | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** updateInviteAccount

### HTTP Request 
`***POST*** /api/invite` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| managedUserVM | body | managedUserVM | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/MERCHANT_ADMIN/USERS
## ***GET*** 

**Summary:** getAllUsersByMerchantAdmin

### HTTP Request 
`***GET*** /api/merchant_admin/users` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/MERCHANTS
## ***POST*** 

**Summary:** createMerchant

### HTTP Request 
`***POST*** /api/merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| merchantBO | body | merchantBO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateMerchant

### HTTP Request 
`***PUT*** /api/merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| merchantBO | body | merchantBO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/MERCHANTS/{UUID}
## ***GET*** 

**Summary:** getMerchant

### HTTP Request 
`***GET*** /api/merchants/{uuid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path | uuid | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/PROFILE-INFO
## ***GET*** 

**Summary:** getActiveProfiles

### HTTP Request 
`***GET*** /api/profile-info` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/REGISTER
## ***POST*** 

**Summary:** registerAccount

### HTTP Request 
`***POST*** /api/register` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| managedUserVM | body | managedUserVM | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/REGISTER-MERCHANT-USER
## ***POST*** 

**Summary:** registerAccountForMerchantUser

### HTTP Request 
`***POST*** /api/register-merchant-user` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| managedUserVM | body | managedUserVM | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/USERS
## ***GET*** 

**Summary:** getAllUsers

### HTTP Request 
`***GET*** /api/users` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createUser

### HTTP Request 
`***POST*** /api/users` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| managedUserVM | body | managedUserVM | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateUser

### HTTP Request 
`***PUT*** /api/users` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| managedUserVM | body | managedUserVM | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/USERS/{LOGIN}
## ***GET*** 

**Summary:** getUser

### HTTP Request 
`***GET*** /api/users/{login}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| login | path | login | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteUser

### HTTP Request 
`***DELETE*** /api/users/{login}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| login | path | login | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/VERIFY_EMAIL
## ***GET*** 

**Summary:** finishVerifyEmail

### HTTP Request 
`***GET*** /api/verify_email` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| key | query | key | Yes | string |
| email | query | email | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** requestVerifyEmail

### HTTP Request 
`***POST*** /api/verify_email` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| email | body | email | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/DOWNLOAD_BILL
## ***POST*** 

**Summary:** downloadBill

### HTTP Request 
`***POST*** /api/wechatpay/v1/download_bill` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| requestDTO | body | requestDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/ECHO/{REQUEST}
## ***GET*** 

**Summary:** echo

### HTTP Request 
`***GET*** /api/wechatpay/v1/echo/{request}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| request | path | request | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/NOTIFY_PAYMENT
## ***POST*** 

**Summary:** notifyPayment

### HTTP Request 
`***POST*** /api/wechatpay/v1/notify_payment` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| content | body | content | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/ORDER_QUERY
## ***POST*** 

**Summary:** orderQuery

### HTTP Request 
`***POST*** /api/wechatpay/v1/order_query` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| requestDTO | body | requestDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/PARTIALLYREFUND
## ***POST*** 

**Summary:** processPartialRefund

### HTTP Request 
`***POST*** /api/wechatpay/v1/partiallyrefund` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| weChatRefundRequestDTO | body | weChatRefundRequestDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/PROCESSPAYMENT
## ***POST*** 

**Summary:** processPayment

### HTTP Request 
`***POST*** /api/wechatpay/v1/processPayment` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| weChatPaymentRequestDTO | body | weChatPaymentRequestDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/QRCODE/{TRANSACTIONID}
## ***GET*** 

**Summary:** qrcode

### HTTP Request 
`***GET*** /api/wechatpay/v1/qrcode/{transactionId}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| transactionId | path | transactionId | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WECHATPAY/V1/REFUND
## ***POST*** 

**Summary:** processRefund

### HTTP Request 
`***POST*** /api/wechatpay/v1/refund` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| weChatRefundRequestDTO | body | weChatRefundRequestDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-ACCOUNT-FEATURES
## ***GET*** 

**Summary:** getAllWtAccountFeatures

### HTTP Request 
`***GET*** /api/wt-account-features` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtAccountFeature

### HTTP Request 
`***POST*** /api/wt-account-features` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtAccountFeatureDTO | body | wtAccountFeatureDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtAccountFeature

### HTTP Request 
`***PUT*** /api/wt-account-features` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtAccountFeatureDTO | body | wtAccountFeatureDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-ACCOUNT-FEATURES/{ID}
## ***GET*** 

**Summary:** getWtAccountFeature

### HTTP Request 
`***GET*** /api/wt-account-features/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtAccountFeature

### HTTP Request 
`***DELETE*** /api/wt-account-features/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-ACCOUNTS
## ***GET*** 

**Summary:** getAllWtAccounts

### HTTP Request 
`***GET*** /api/wt-accounts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtAccount

### HTTP Request 
`***POST*** /api/wt-accounts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtAccountDTO | body | wtAccountDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtAccount

### HTTP Request 
`***PUT*** /api/wt-accounts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtAccountDTO | body | wtAccountDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-ACCOUNTS/{ID}
## ***GET*** 

**Summary:** getWtAccount

### HTTP Request 
`***GET*** /api/wt-accounts/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtAccount

### HTTP Request 
`***DELETE*** /api/wt-accounts/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-EMAIL-TEMPLATES
## ***GET*** 

**Summary:** getAllWtEmailTemplates

### HTTP Request 
`***GET*** /api/wt-email-templates` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtEmailTemplate

### HTTP Request 
`***POST*** /api/wt-email-templates` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtEmailTemplateDTO | body | wtEmailTemplateDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtEmailTemplate

### HTTP Request 
`***PUT*** /api/wt-email-templates` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtEmailTemplateDTO | body | wtEmailTemplateDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-EMAIL-TEMPLATES/TEST
## ***POST*** 

**Summary:** testWtEmailTemplate

### HTTP Request 
`***POST*** /api/wt-email-templates/test` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtEmailTemplateDTO | body | wtEmailTemplateDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-EMAIL-TEMPLATES/{ID}
## ***GET*** 

**Summary:** getWtEmailTemplate

### HTTP Request 
`***GET*** /api/wt-email-templates/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtEmailTemplate

### HTTP Request 
`***DELETE*** /api/wt-email-templates/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-EMAILS
## ***GET*** 

**Summary:** getAllWtEmails

### HTTP Request 
`***GET*** /api/wt-emails` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtEmail

### HTTP Request 
`***POST*** /api/wt-emails` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtEmailDTO | body | wtEmailDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtEmail

### HTTP Request 
`***PUT*** /api/wt-emails` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtEmailDTO | body | wtEmailDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-EMAILS/RETRY
## ***POST*** 

**Summary:** retry

### HTTP Request 
`***POST*** /api/wt-emails/retry` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtEmailDTO | body | wtEmailDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-EMAILS/{ID}
## ***GET*** 

**Summary:** getWtEmail

### HTTP Request 
`***GET*** /api/wt-emails/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtEmail

### HTTP Request 
`***DELETE*** /api/wt-emails/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-MERCHANT/AUTHENTICATE
## ***POST*** 

**Summary:** authenticateWtMerchant

### HTTP Request 
`***POST*** /api/wt-merchant/authenticate` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| authenticateMerchantVM | body | authenticateMerchantVM | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS
## ***GET*** 

**Summary:** getAllWtMerchants

### HTTP Request 
`***GET*** /api/wt-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtMerchant

### HTTP Request 
`***POST*** /api/wt-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtMerchantDTO | body | wtMerchantDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtMerchant

### HTTP Request 
`***PUT*** /api/wt-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtMerchantDTO | body | wtMerchantDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS/ACTIVATE
## ***POST*** 

**Summary:** activateMerchant

### HTTP Request 
`***POST*** /api/wt-merchants/activate` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtMerchantDTO | body | wtMerchantDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS/DEACTIVATE
## ***POST*** 

**Summary:** deactivateMerchant

### HTTP Request 
`***POST*** /api/wt-merchants/deactivate` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtMerchantDTO | body | wtMerchantDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS/MERCHANT/{ID}
## ***GET*** 

**Summary:** getWtMerchantById

### HTTP Request 
`***GET*** /api/wt-merchants/merchant/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS/RESEND
## ***POST*** 

**Summary:** resendInvitationEmail

### HTTP Request 
`***POST*** /api/wt-merchants/resend` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtMerchantDTO | body | wtMerchantDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS/USER
## ***GET*** 

**Summary:** getWtMerchantsByUserLogin

### HTTP Request 
`***GET*** /api/wt-merchants/user` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS/USER/{LOGIN}
## ***GET*** 

**Summary:** getWtMerchantsByUserLogin

### HTTP Request 
`***GET*** /api/wt-merchants/user/{login}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| login | path | login | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-MERCHANTS/{UUID}
## ***GET*** 

**Summary:** getWtMerchant

### HTTP Request 
`***GET*** /api/wt-merchants/{uuid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path | uuid | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtMerchant

### HTTP Request 
`***DELETE*** /api/wt-merchants/{uuid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path | uuid | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-SETTLEMENT-LOGS
## ***GET*** 

**Summary:** getAllWtSettlementLogs

### HTTP Request 
`***GET*** /api/wt-settlement-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtSettlementLog

### HTTP Request 
`***POST*** /api/wt-settlement-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtSettlementLogDTO | body | wtSettlementLogDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtSettlementLog

### HTTP Request 
`***PUT*** /api/wt-settlement-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtSettlementLogDTO | body | wtSettlementLogDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-SETTLEMENT-LOGS/SETTLE
## ***PUT*** 

**Summary:** updateWtSettlementLogWithSettleTime

### HTTP Request 
`***PUT*** /api/wt-settlement-logs/settle` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtSettlementLogDTO | body | wtSettlementLogDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-SETTLEMENT-LOGS/{ID}
## ***DELETE*** 

**Summary:** deleteWtSettlementLog

### HTTP Request 
`***DELETE*** /api/wt-settlement-logs/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-SETTLEMENT-LOGS/{SETTLEMENTUUID}/WT-TRANSACTIONS
## ***GET*** 

**Summary:** getWtSettlementLogTransaction

### HTTP Request 
`***GET*** /api/wt-settlement-logs/{settlementUuid}/wt-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| settlementUuid | path | settlementUuid | Yes | string |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-SETTLEMENT-LOGS/{UUID}
## ***GET*** 

**Summary:** getWtSettlementLog

### HTTP Request 
`***GET*** /api/wt-settlement-logs/{uuid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path | uuid | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-TRANSACTION-CURRENCIES
## ***GET*** 

**Summary:** getAllWtTransactionCurrencies

### HTTP Request 
`***GET*** /api/wt-transaction-currencies` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtTransactionCurrency

### HTTP Request 
`***POST*** /api/wt-transaction-currencies` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionCurrencyDTO | body | wtTransactionCurrencyDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtTransactionCurrency

### HTTP Request 
`***PUT*** /api/wt-transaction-currencies` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionCurrencyDTO | body | wtTransactionCurrencyDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-TRANSACTION-CURRENCIES/{ID}
## ***GET*** 

**Summary:** getWtTransactionCurrency

### HTTP Request 
`***GET*** /api/wt-transaction-currencies/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtTransactionCurrency

### HTTP Request 
`***DELETE*** /api/wt-transaction-currencies/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-TRANSACTION-ERROR-LOGS
## ***GET*** 

**Summary:** getAllWtTransactionErrorLogs

### HTTP Request 
`***GET*** /api/wt-transaction-error-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtTransactionErrorLog

### HTTP Request 
`***POST*** /api/wt-transaction-error-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionErrorLogDTO | body | wtTransactionErrorLogDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtTransactionErrorLog

### HTTP Request 
`***PUT*** /api/wt-transaction-error-logs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionErrorLogDTO | body | wtTransactionErrorLogDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-TRANSACTION-ERROR-LOGS/{ID}
## ***GET*** 

**Summary:** getWtTransactionErrorLog

### HTTP Request 
`***GET*** /api/wt-transaction-error-logs/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtTransactionErrorLog

### HTTP Request 
`***DELETE*** /api/wt-transaction-error-logs/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-TRANSACTION-JOURNALS
## ***GET*** 

**Summary:** getAllWtTransactionJournals

### HTTP Request 
`***GET*** /api/wt-transaction-journals` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtTransactionJournal

### HTTP Request 
`***POST*** /api/wt-transaction-journals` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionJournalDTO | body | wtTransactionJournalDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtTransactionJournal

### HTTP Request 
`***PUT*** /api/wt-transaction-journals` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionJournalDTO | body | wtTransactionJournalDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-TRANSACTION-JOURNALS/{ID}
## ***GET*** 

**Summary:** getWtTransactionJournal

### HTTP Request 
`***GET*** /api/wt-transaction-journals/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtTransactionJournal

### HTTP Request 
`***DELETE*** /api/wt-transaction-journals/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-TRANSACTIONS
## ***GET*** 

**Summary:** getAllWtTransactions

### HTTP Request 
`***GET*** /api/wt-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtTransaction

### HTTP Request 
`***POST*** /api/wt-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionDTO | body | wtTransactionDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtTransaction

### HTTP Request 
`***PUT*** /api/wt-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtTransactionDTO | body | wtTransactionDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-TRANSACTIONS/{ID}
## ***DELETE*** 

**Summary:** deleteWtTransaction

### HTTP Request 
`***DELETE*** /api/wt-transactions/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-TRANSACTIONS/{UUID}
## ***GET*** 

**Summary:** getWtTransaction

### HTTP Request 
`***GET*** /api/wt-transactions/{uuid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path | uuid | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-TRANSACTIONS/{UUID}/REFUNDS
## ***GET*** 

**Summary:** getRefundWtTransactions

### HTTP Request 
`***GET*** /api/wt-transactions/{uuid}/refunds` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path | uuid | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-USER-MERCHANTS
## ***GET*** 

**Summary:** getAllWtUserMerchants

### HTTP Request 
`***GET*** /api/wt-user-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtUserMerchant

### HTTP Request 
`***POST*** /api/wt-user-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtUserMerchantDTO | body | wtUserMerchantDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtUserMerchant

### HTTP Request 
`***PUT*** /api/wt-user-merchants` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtUserMerchantDTO | body | wtUserMerchantDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-USER-MERCHANTS/ROLES-NAMES/{ID}
## ***GET*** 

**Summary:** getAuthoritiesAndMerchantNamesByUserId

### HTTP Request 
`***GET*** /api/wt-user-merchants/roles-names/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-USER-MERCHANTS/{ID}
## ***GET*** 

**Summary:** getWtUserMerchant

### HTTP Request 
`***GET*** /api/wt-user-merchants/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-WX-MERCHANT-CONFIGS
## ***GET*** 

**Summary:** getAllWtWxMerchantConfigs

### HTTP Request 
`***GET*** /api/wt-wx-merchant-configs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtWxMerchantConfig

### HTTP Request 
`***POST*** /api/wt-wx-merchant-configs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtWxMerchantConfigDTO | body | wtWxMerchantConfigDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtWxMerchantConfig

### HTTP Request 
`***PUT*** /api/wt-wx-merchant-configs` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtWxMerchantConfigDTO | body | wtWxMerchantConfigDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-WX-MERCHANT-CONFIGS/{ID}
## ***GET*** 

**Summary:** getWtWxMerchantConfig

### HTTP Request 
`***GET*** /api/wt-wx-merchant-configs/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***DELETE*** 

**Summary:** deleteWtWxMerchantConfig

### HTTP Request 
`***DELETE*** /api/wt-wx-merchant-configs/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |

# /API/WT-WX-TRANSACTIONS
## ***GET*** 

**Summary:** getAllWtWxTransactions

### HTTP Request 
`***GET*** /api/wt-wx-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Page number of the requested page | No | integer |
| size | query | Size of a page | No | integer |
| sort | query | Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported. | No | array |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***POST*** 

**Summary:** createWtWxTransaction

### HTTP Request 
`***POST*** /api/wt-wx-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtWxTransactionDTO | body | wtWxTransactionDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

## ***PUT*** 

**Summary:** updateWtWxTransaction

### HTTP Request 
`***PUT*** /api/wt-wx-transactions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| wtWxTransactionDTO | body | wtWxTransactionDTO | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

# /API/WT-WX-TRANSACTIONS/{ID}
## ***GET*** 

**Summary:** getWtWxTransaction

### HTTP Request 
`***GET*** /api/wt-wx-transactions/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | id | Yes | long |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
