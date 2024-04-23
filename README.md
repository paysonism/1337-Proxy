# 1337 Proxy

An advanced web proxy that allows you to access websites privately aswell as **unblock any website**.

# Updates

[4-22-24] Initial Release

[SOON] New UI

# Configuration
Configure proxy for both client-hooking & service worker in `uv.config.js`

```javascript
self.__uv$config = {
    bare: '/bare/',
    prefix: '/service/',
    encodeUrl: Ultraviolet.codec.xor.encode,
    decodeUrl: Ultraviolet.codec.xor.decode,
    handler: '/uv.handler.js',
    bundle: '/uv.bundle.js',
    config: '/uv.config.js',
};
```


# Example Usage

```javascript
importScripts('/PATHTOSCRIPTS/uv.sw.js');

const sw = new UVServiceWorker();

self.addEventListener('fetch', event =>
    event.respondWith(
        sw.fetch(event)
    )
);
```

# Support

Need help? Feel free to contact me on [telegram](https://t.me/payson1337). I do freelance development and can dev almost anything. Feel free to check out my other projects [here](https://github.com/paysonism?tab=repositories)

# Credits

Made By [Payson](https://github.com/paysonism)