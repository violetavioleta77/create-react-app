-proiect-dirigenție/
├── client/
│   ├── public/
│   │   ├── index.html
│   └── src/
│       ├── App.js
│       ├── index.js
│       └── components/
├── server/
│   ├── models/
│   ├── routes/
│   ├── app.js
│   └── server.js
├── package.json
└── package-lock.jsone the other files.

You may create subdirectories inside `src`. For faster rebuilds, only files inside `src` are processed by webpack. You need to **put any JS and CSS files inside `src`**, otherwise webpack won’t see them.

Only files inside `public` can be used from `public/index.html`. Read instructions below for using assets from JavaScript and HTML.

You can, however, create more top-level directories. They will not be included in the production build so you can use them for things like documentation.

If you have Git installed and your project is not part of a larger repository, then a new repository will be initialized resulting in an additional top-level `.git` directory.
