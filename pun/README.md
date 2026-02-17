# Pun - JavaScript & TypeScript Generic

### From their [site](https://pun-three.vercel.app)

This egg is designed to run any generic Pun application.

There is an option to allow a user to upload their own files to run a server.

The startup configs and commands may need changing to actually function properly.

### Configuration

The server will be stuck as starting until the egg Start Configuration is modified. You have to edit the text to match something your application will print for Pterodactyl panel to detect it as running.

You can use arrays to have multiple different values when different applications are being used

```json
{
  "done":[
    "change this text 1",
    "change this text 2"
  ]
}
```
