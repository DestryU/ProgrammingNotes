Raw HTML is a simple kind of "language" that lets you write code that is read directly by a browser[^1]. The problem, especially nowadays, is that reading raw HTML poses a pretty significant security risk to your computer - *lots* of things can be accessed through the use of your browser. One answer to this problem, and an answer that offers many other benefits, is to use a 'build tool' or 'bundler'[^2].

[^1]: Any HTML file can be run by opening it. This doesn't mean you should.
[^2]: Bundler is a more outdated term, but it will still creep up from time to time.

There are lot of build tools available for use such as Webpack, Vite, Gulp, Parcel, and more. Webpack stands as one of the most popular build tools, but these notes are going to focus on Vite.