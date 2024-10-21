## Early description of the project
### Implication…
To help web development beginners to start building their project with this template as a handful and versatile foundation rather than having to start all over from scratch. 
### Goal…
- A final template for swift web development with minimal dependencies yet full-fledged, versatile, performant, reliable, and efficient.
> [!TIP] 
> Plain → Utilities → Templating → Building → Deployment → Maintenance
### Uses…
- Comprehensive REST APIs to handle HTTP requests from the client
- HTMX-like custom HTML element attributes for HTTP request methods (`GET`, `POST`, `PUT`, and `DELETE`) to specify URL endpoint, and for target element specifying CSS selector, but custom boolean attribute ones for triggering events (`click`, `mouseover`, ...) as well as for target element's property (`innerHTML`, `outerHTML`, ...), all of which is defined in Javascript
- Session to enable auto-save for user-input data, and to achieve persistent log-in
- Separation of concerns (R.I.P. PHP) between server side and client side, as well as a partition for the static site generator which is to be rendered at build time unlike the two
- HTML templating in `templates` package with block definition and inheritance directives ready to replace the template directives, whose output will be rendered and stored in `builds` package
- SQL databases alongside alternatives to them, such as any NoSQL databases and even server-located/internal databases, may it be on cloud or on premise
- Basic implementations of Server-Side Rendering (SSR) by parsing and rendering at once on page request, or Static Site Generation (SSG) by parsing at build time which later can be rendered on page request
- Basic architecture for both Single-Page App (SPA) and Multi-Page App (MPA)
- Asynchronous DOM manipulation for seamless page and element transition/animation with minimal JavaScript bloating as possible
- Web sockets for live stream using UDP to maintain continuous connection without unnecessary TCP handshaking 
- Essential components leveraging Bootstrap CSS styling
- Succinct documentation about the template
- Comments added for some insightful cheat-sheets and idioms within the template for hands-on or observative learning 

