### CREATE THE CLIENT APP INTO SPRING PROJECT

1. Adding react: Here we are going to use `npx` (included in the latest versions of `npm`).

```bash
# Command
npx create-react-app <app-name>

# Example
npx create-react-app client
```

2. Once completed previous step, go to the client folder `cd client`, and execute `npm start`. 
This will open a web browser on your desktop. You will see:

```bash
Compiled successfully!

You can now view client in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.174.128:3000

Note that the development build is not optimized.
To create a production build, use npm run build.

```

Previous example means that you can access to you client app in `localhost:3000`

3. So far, we can see `backend` project running at `http://localhost:8585` and the `client` 
running at `http://localhost:3000`. So we would like to able to call services in the backend
and display the results in the frontend. So we will need to perform the following configuration 
in `client/package.json`.


















