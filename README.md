## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
    "forms":[
    {
        "id":1,
        "form":"Know yoru client form",
        "date":"Jun 22, 2023"
    },
    {
        "id":2,
        "form":"Foreign Account Tax Compliance Act",
        "date":"Jun 22, 2023"
    },    {
        "id":3,
        "form":"Custodian Form",
        "date":"Jun 22, 2023"
    },    {
        "id":4,
        "form":"AML Form",
        "date":"Jun 22, 2023"
    },    {
        "id":5,
        "form":"Know Your Client Form",
        "date":"Jun 22, 2023"
    }
]
}
```

## Reference

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
