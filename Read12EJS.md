# EJS Partials
Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

* In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters (you could change these delimiters if you really wanted to).
Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.
Note: The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’, etc…

# Why EJS?
There are several templating systems out there with their merits and demerits, I personally use EJS because of its simplicity in syntax and logic. Its also very easy to set up.

- Partials are rendered synchronously, so they will block Sails from serving more requests until they're done loading. It's something to keep in mind while developing your app, especially if you anticipate a large number of connections.
- Built-in support for partials in Sails is only for the default view engine, ejs. If you decide to customize your Sails install and use a view engine other than ejs, then please be aware that support for partials (sometimes known as "blocks", "includes", etc.) may or may not be included, and that the usage will vary. Refer to the documentation for your view engine of choice for more information on its syntax and conventions.
