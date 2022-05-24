# ASSIGN DASHBOARD TO NEW USER

This rule chain assigns predefined dashboard to new Thingsboard tenant admin or customer user.

**IMPORTANT:** The rule chain uses another chain called [Thingsboard API token](/chain/tb_api_token).

## Configuration

**IMPORTANT**: To get things working several placeholders should be replaced with the real data.
1. For this rule chain:
    - **NAME_OF_DASHBOARD_FOR_USERS**
    - **NAME_OF_DASHBOARD_FOR_ADMINS**

2. Placeholders for [Thingsboard API token](/chain/tb_api_token) chain is described [here](/chain/tb_api_token#configuration).

You can do this in two ways:

### (1) Before importing

1. Download the rule chains' JSON files.
2. Replace placeholders in the file. Here are links:
    - [NAME_OF_DASHBOARD_FOR_USERS](/chain/assign-dashboard-to-new-user/assign_dashboard_to_new_user.json#L222)
    - [NAME_OF_DASHBOARD_FOR_ADMINS](/chain/assign-dashboard-to-new-user/assign_dashboard_to_new_user.json#L222)
3. Placeholders for [Thingsboard API token](/chain/tb_api_token#1-before-importing) rule chain.
4. Import files to Thingsboard.

### (2) After importing
1. Download the rule chains' JSON files.
2. Import the files to Thingsboard.
3. Open this rule chain.
4. Open the _Rule chain_ node called _Get API token_ and specify the [Thingsboard API token](/chain/tb_api_token) rule chain in the _Rule chain_ field.
5. To replace the **NAME_OF_DASHBOARD_FOR_USERS** and **NAME_OF_DASHBOARD_FOR_ADMINS** placeholders open the _Transformation script_ node called _Configuration_ .
6. Placeholders for [Thingsboard API token](/chain/tb_api_token#2-after-importing) rule chain.

## Result

### Tenant's admin
Once new tenant's admin has been created, the predefined dashboard will have been assigned to this user as the home dasboard.

### Customer's user
Once new customer's user has been created, the predefined dashboard will have been assigned both to the customer and to this user as the home dasboard.
