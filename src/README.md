# How Create a PWA app!

- Import a HTML file and watch it magically convert to Markdown
```$ npm install -g @angular/cli```

- Now Generate Project Using the Following Command
```$ ng new pwa-example```

- Move into the new projected you have just created using the command as following
```$ cd pwa-example```

- And add Angular PWA using the following code
```ng add @angular/pwa```

- Install http-server (it is important to install version 0.9.0)
```npm install -g http-server@0.9.0```

- Build app to run the service worker
```ng build --prod```

- Launching Angular PWA Application
```http-server -c-1 dist/pwa-example```

- Now you can access the application at <http://localhost:8080>

- It's possible to audit the PWA app accessing the Chrome DevTools Audits options and click 'Run Audits'
