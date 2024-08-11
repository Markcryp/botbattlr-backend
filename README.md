## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

![Powered by Vercel](https://images.ctfassets.net/e5382hct74si/78Olo8EZRdUlcDUFQvnzG7/fa4cdb6dc04c40fceac194134788a0e2/1618983297-powered-by-vercel.svg)

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
"bots": [
      {
        "id": 101,
        "name": "wHz-93",
        "health": 94,
        "damage": 20,
        "armor": 63,
        "bot_class": "Support",
        "catchphrase": "1010010101001101100011000111101",
        "avatar_url": "https://robohash.org/nostrumrepellendustenetur.png?size=300x300&set=set1",
        "created_at": "2018-10-02T19:55:10.800Z",
        "updated_at": "2018-10-02T19:55:10.800Z"
      },
      {
        "id": 102,
        "name": "RyM-66",
        "health": 86,
        "damage": 36,
        "armor": 77,
        "bot_class": "Medic",
        "catchphrase": "0110011100000100011110100110011000011001",
        "avatar_url": "https://robohash.org/quidemconsequaturaut.png?size=300x300&set=set1",
        "created_at": "2018-10-02T19:55:10.827Z",
        "updated_at": "2018-10-02T19:55:10.827Z"
      },
```

## Reference

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
