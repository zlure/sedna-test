## Step one: register the app
## Step two: get the code

First, clone the repo.

Second, modify the config.

- `index.js`: replace the values of the `clientID` and `clientSecret` variables.
- `public/index.html`: replace the values of the `client_id` variable.

Third, install the dependencies.

```bash
$ npm install
```

## Step three: run the server

Now, run the server.

```bash
$ node index.js
```

Visit http://localhost:8080 in your browser, and click the link to login GitHub.

