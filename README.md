# caliring-link-forwarding
Simple url forwarding application hosted with firebase

The firebase.json contains the link the website 301 redirects. The structure is as the following:

```
"redirects": [
      {
        "source": "/",
        "destination": "https://your-website.com",
        "type": 301
      }
    ]
```

Source means the path of the url, example "https://my-website.com/source", destination means the url you want to redirect to.