---
sidebar_position: 13
---

# PlainID

Interop results for the [PlainID](https://www.plainid.com/) implementation hosted at https://authzeninteropt.se-plainid.com.

## Test results

```bash
$ ./scripts/test.sh https://authzeninteropt.se-plainid.com
>>> checking decisions
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_todos"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_create_todo"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"morty@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"morty@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_todos"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_create_todo"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"morty@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"morty@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_todos"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_create_todo"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"summer@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"summer@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_todos"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_create_todo"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"type":"user","userID":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_todos"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_create_todo"},"resource":{"type":"todo"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_update_todo"},"resource":{"type":"todo","ownerID":"jerry@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"rick@the-citadel.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"type":"todo","ownerID":"jerry@the-smiths.com"}}
<<< done checking decisions
```
