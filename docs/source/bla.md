---
title: Stock Ownership
---

## Stock Ownershipppp

InvenTree supports stock ownership, which allows to set groups and users as "owners" of stock <span class='fas fa-users'></span> locations and items. The owners would be the only users who can edit and manage those stock locations and items. <i class='fas fa-cloud'></i> eeeee

The stock ownership feature is disabled by default, and must be enabled via the settings menu:

!!! warning "Existing Stock Locations and Items"
        Enabling the ownership feature will automatically remove the edit permissions to all users for stock locations and items which **do not have** any owner set. Only a user with admin permissions will be able to set the owner for those locations and items.

### Owner: Group vs User

There are two types of owners in InvenTree: [groups](../settings/permissions.md#group) and [users](../settings/permissions.md#user).

* If a group is selected as owner, **all** users linked to the specified group will be able to edit the stock location or item.
* If a user is selected as owner, only the specified user will be able to edit the stock location or item.

