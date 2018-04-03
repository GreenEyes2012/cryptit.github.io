# Crypt-It
@fa[lock fa-5x]
### Secure encryption online or offline from any device.

---

## CryptoJS Based App
@fa[key fa-3x]

<table>
  <tr>
    <th>SHA-256</th>
    <th>SHA-1</th> 
    <th>AES</th>
    <th>Rabbit</th>
  </tr>
  <tr>
    <td>SHA-512</td>
    <td>DES</td>
    <td>PBKDF2</td>
    <td>RC4</td>
  </tr>
  <tr class="fragment">
    <td>SHA-3</td>
    <td>Triple DES</td>
    <td>94</td>
    <td>RC4Drop</td>
  </tr>
</table>
<br>

---

---?video=http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4
- Slide with video as background |
---

## Features

- Mobile Ready |
- Releases available for Windows, Linux, & MacOS |
- Client-Side Encryption |
- Custom Logo, TOC, and Footnotes |

---

@title[Code Block]

<p><span class="slide-title">Code Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting), [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents), and [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

### Questions?

<br>

@fa[github gp-contact](cryptit)

---?image=assets/image/gitpitch-audience.jpg

@title[Download Now!]

### <span class="white">Protect your data!</span>
### [Start using @fa[fa-download gp-download]](https://gitpitch.com/template/download/aqua)

