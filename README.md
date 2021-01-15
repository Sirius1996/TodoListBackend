# TodoListBackend
The backend server for TodoList app implemented by Golang

## Tables
### Task

| Attribute | Type |
| --------- | ---- |
| id | int |
| title | string |
| descption | string |
| duration | int |
| remaintime | int |
| typestr | string |
| isfinish | bool |
| isgrouptask | bool |

### User

| Attribute | Type |
| --------- | ---- |
| id | int |
| name | string |
| email | string |
| passwd | string |

### UserTaskList

| Attribute | Type |
| --------- | ---- |
| userid | int |
| taskid | int |

### UserFriendList

| Attribute | Type |
| --------- | ---- |
| userid | int |
| friendid| int |
