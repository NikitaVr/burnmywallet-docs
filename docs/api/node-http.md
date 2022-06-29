---
sidebar_position: 4
---

# Node - Http

Docusaurus creates a **page for each blog post**, but also a **blog index page**, a **tag system**, an **RSS** feed...

## Create your first Post

Create a file at `blog/2021-02-28-greetings.md`:

```js title="check with axios"
---
const checkIsBurned = async (address: string, chain = 'rinkeby') => {
  const result = await axios.get(
    `https://burnmywallet.com/api/isBurned?address=${address}&chain=${chain}`
  )
  console.log('handleSearch after api call', result.data)

  const data = result.data as IsBurnedResponse

  return data.hacked
}
---

Congratulations, you have made your first post!

Feel free to play around and edit this post as much you like.
```

A new blog post is now available at `http://localhost:3000/blog/greetings`.
