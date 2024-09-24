Raw HTML is a simple kind of "language" that lets you write code that is read directly by a browser[^1]. The problem, especially nowadays, is that reading raw HTML poses a pretty significant security risk to your computer - *lots* of things can be accessed through the use of your browser. One answer to this problem, and an answer that offers many other benefits, is to use a 'build tool' or 'bundler'[^2].

[^1]: Any HTML file can be run by opening it. This doesn't mean you should.
[^2]: Bundler is a more outdated term, but it will still creep up from time to time.

There are lot of build tools available for use such as Webpack, Vite, Gulp, Parcel, and more. Webpack stands as one of the most popular build tools, but these notes are going to focus on Vite.

Vite does a number of things for you, as the user. For starters, it lets you write web code (HTML + CSS + JS) and compile that into a finalized website *wihtout* the need to upload and deploy that website[^3]. But on top of that, build tools will perform a bunch of other functions for you, such as optimizing, cache breaking, source mapping, running local servers, and so on.

[^3]: Specifically, build tools let you build the website locally to ensure that it works. Using a build tool to build your website does **not** mean that your website is out in the world, just that it is capable of running.

Part of why I want to focus on Vite is not only because of its speed, which is a big factor, but because of its stability and the affordances it has for plugins and expansion. For my specific purposes, this was because of its integrations with GLSL and React. 