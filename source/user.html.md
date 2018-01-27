---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell

toc_footers:
  - <a href='http://www.baidu.com'>Baidu for Help</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - user
search: true
---

# Introduction
 This is My first test of slate API doc

## My testapi

```shell
curl "http://example.com/api/user/2"
  -X DELETE
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name" : "zhaofx"
}
```

This endpoint query a specific user.

### HTTP Request

`GET http://example.com/kittens/<ID>&name=<name>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete
name | the name of user

