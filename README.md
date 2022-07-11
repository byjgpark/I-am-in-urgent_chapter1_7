# 응급해

급한 응급실이 필요할때 주변 응급실을 찾아주는 웹기반 서비스 입니다


## Screenshots

<img width="985" alt="Screen Shot 2022-07-11 at 6 49 39 PM" src="https://user-images.githubusercontent.com/48500149/178240424-6a7599ce-dc30-4cac-a746-174b18f8f9c3.png">



## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.
