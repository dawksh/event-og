<a href="https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fog-image&demo-title=OG%20Image%20Generator&demo-description=A%20service%20that%20generates%20dynamic%20Open%20Graph%20images&demo-url=https%3A%2F%2Fog-image.vercel.app%2F&demo-image=https%3A%2F%2Fog-image.vercel.app%2FOpen%2520Graph%2520Image%2520as%2520a%2520Service.png%3Ftheme%3Dlight%26md%3D1%26fontSize%3D95px%26images%3Dhttps%253A%252F%252Fassets.vercel.com%252Fimage%252Fupload%252Ffront%252Fassets%252Fdesign%252Fzeit-black-triangle.svg"><img src="https://vercel.com/button" alt="Deploy with Vercel" align="right" width="128"/></a>

# [Open Graph Image as a Service](https://og-image.vercel.app)

<a href="https://twitter.com/vercel">
    <img align="right" src="https://og-image.vercel.app/tweet.png" height="300" />
</a>

Serverless service that generates dynamic Open Graph images that you can embed in your `<meta>` tags.

For each keystroke, headless chromium is used to render an HTML page and take a screenshot of the result which gets cached.

See the image embedded in the tweet for a real use case.

## Why it's not working?

Make sure you have node v14.x is on your system for dev & node v14.x is setup on vercel under settings/general. Do not waste 2 hours like me when all I had to do was change the version.
