---
sidebar_position: 12
---

# EmpowerID

Interop results for the [EmpowerID](https://www.empowerid.com/) implementation hosted at `https://authzen-demo.eidlabs.net`.

## Test results

```bash
yarn test https://authzen-demo.eidlabs.net 1.0-implementers-draft markdown
yarn run v1.22.22
$ node build/test/runner.js https://authzen-demo.eidlabs.net 1.0-implementers-draft markdown
```
<table>
  <tr>
    <th>result</th>
    <th>request</th>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "beth@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "rick@the-citadel.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_todos"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_create_todo"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b91",
    "properties": {
      "ownerID": "morty@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b91",
    "properties": {
      "ownerID": "morty@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "beth@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "morty@the-citadel.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_todos"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_create_todo"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "_note": "ID for Morty",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b91",
    "properties": {
      "ownerID": "morty@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDE2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b91",
    "properties": {
      "ownerID": "morty@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "beth@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "summer@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_todos"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_create_todo"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b93",
    "properties": {
      "ownerID": "summer@the-smiths.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDI2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b93",
    "properties": {
      "ownerID": "summer@the-smiths.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "beth@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "beth@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_todos"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_create_todo"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b94",
    "properties": {
      "ownerID": "beth@the-smiths.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDM2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b94",
    "properties": {
      "ownerID": "beth@the-smiths.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "beth@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_user"
  },
  "resource": {
    "type": "user",
    "id": "jerry@the-smiths.com"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_read_todos"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_create_todo"
  },
  "resource": {
    "type": "todo",
    "id": "todo-1"
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_update_todo"
  },
  "resource": {
    "type": "todo",
    "id": "240d0db-8ff0-41ec-98b2-34a096273b95",
    "properties": {
      "ownerID": "jerry@the-smiths.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "7240d0db-8ff0-41ec-98b2-34a096273b92",
    "properties": {
      "ownerID": "rick@the-citadel.com"
    }
  }
}
```

  </td>
  </tr>
  <tr>
    <td bgColor="green">PASS</td>
    <td>

```js
{
  "subject": {
    "type": "user",
    "id": "CiRmZDQ2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"
  },
  "action": {
    "name": "can_delete_todo"
  },
  "resource": {
    "type": "todo",
    "id": "240d0db-8ff0-41ec-98b2-34a096273b95",
    "properties": {
      "ownerID": "jerry@the-smiths.com"
    }
  }
}
```

  </td>
  </tr>
</table>