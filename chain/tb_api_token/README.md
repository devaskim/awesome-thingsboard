# THINGSBOARD API TOKEN

This rule chain [logs in](https://demo.thingsboard.io/swagger-ui/#/login-endpoint/loginPost) as an existing Thingsboard user and puts the retrieved JWT token and refresh token to a message's metadata. In further you can use this token to call [Thinsboard REST API](https://demo.thingsboard.io/swagger-ui/).

**IMPORTANT**: Disregarding the result of the logging-in procedure the message payload will be the same as it was before entering this rule chain.

## Configuration

**IMPORTANT**: To get things working several placeholders should be replaced with the real data:
- **THINGSBOARD_URL**
- **THINGSBOARD_ACCOUNT_EMAIL**
- **THINGSBOARD_ACCOUNT_PASSWORD**

You can do this in two ways:

### (1) Before importing

1. Download the rule chain JSON file.
2. Replace placeholders in the file. Here are links:
    - [THINGSBOARD_URL](https://github.com/devaskim/awesome-thingsboard/blob/main/chain/tb_api_token/tb_api_token.json#L65)
    - [THINGSBOARD_ACCOUNT_EMAIL](https://github.com/devaskim/awesome-thingsboard/blob/main/chain/tb_api_token/tb_api_token.json#L99)
    - [THINGSBOARD_ACCOUNT_PASSWORD](https://github.com/devaskim/awesome-thingsboard/blob/main/chain/tb_api_token/tb_api_token.json#L99)
3. Import the file to Thingsboard.

### (2) After importing
1. Download the rule chain JSON file.
2. Import the file to Thingsboard.
3. To replace the **THINGSBOARD_ACCOUNT_EMAIL** and **THINGSBOARD_ACCOUNT_PASSWORD** placeholders open the _Transformation script_ node called _Login credentials_ .
4. To replace the **THINGSBOARD_URL** placeholder open the _Rest API call_ node called _Login_ .

## Result

**IMPORTANT**: Disregarding the result of the logging-in procedure the message payload will be the same as it was before entering this rule chain.

If the logging-in procedure was succesful the metadata of an output message will **addiotionally** contain `token` and `refreshToken` keys:
```
{
  "refreshToken": "eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJkeW9zaWNrODlAZ21haWwuY29tIiwic2NvcGVzIjpbIlJFRlJFU0hfVE9LRU4iXSwidXNlcklkIjoiMzYzMDdhODAtYTA3NC0xMWVjLTgwZTItZTExNjk4MzIzZTRiIiwiaXNQdWJsaWMiOmZhbHNlLCJpc3MiOiJ0aGluZ3Nib2FyZC5pbyIsImp0aSI6Ijg1N2RkMWE4LWZlNTItNDIxYy04YzRlLWM4YzZkNmRjYmE2YSIsImlhdCI6MTY1Mjk4NzYxNiwiZXhwIjoxNjUzNTkyNDE2fQ.XxR3HWK2IHMZBmxRA2XaHHVirqu4GfUCXT3Rrx0z9rgDVVdjTgqm-G9IXZB8gvq7Kzvvz3C-OV57IO8srYQF5w",
  "token": "eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJkeW9zaWNrODlAZ21haWwuY29tIiwic2NvcGVzIjpbIlRFTkFOVF9BRE1JTiJdLCJ1c2VySWQiOiIzNjMwN2E4MC1hMDc0LTExZWMtODBlMi1lMTE2OTgzMjNlNGIiLCJmaXJzdE5hbWUiOiJEZW5pcyIsImVuYWJsZWQiOnRydWUsImlzUHVibGljIjpmYWxzZSwidGVuYW50SWQiOiJhZWYxMTBjMC1hMDczLTExZWMtODBlMi1lMTE2OTgzMjNlNGIiLCJjdXN0b21lcklkIjoiMTM4MTQwMDAtMWRkMi0xMWIyLTgwODAtODA4MDgwODA4MDgwIiwiaXNzIjoidGhpbmdzYm9hcmQuaW8iLCJpYXQiOjE2NTI5ODc2MTYsImV4cCI6MTY1Mjk5NjYxNn0.b_PRViDYx6wFXHwdobYI8uTCMPDcyG_nyoW8O6bTdm3XFvR-lDjhBI9UrlTq1nCZb0Ex2f7JXcDTTF0S1YLK6A",
}
```
