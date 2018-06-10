### Login Server

A ready to ship node js login back-end using passport and mongodb

Create config/dev.js and put your **mongodbURI, googleClientID, googleClientSecret, cookieKey** values

**config/dev.js**
```
module.exports = {
    googleClientID: "",
    googleClientSecret: "",
    mongodbURI: "",
    cookieKey: ""
}
```

```
npm run start

open http://localhost:5000/
```

All set! :)
