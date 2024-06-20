# LearningWebpacks
At its core, webpack is a static module bundler for modern JavaScript applications. When webpack processes your application, it internally builds a dependency graph from one or more entry points and then combines every module your project needs into one or more bundles, which are static assets to serve your content from.
When you use Node.js and npm to manage dependencies, you typically have a node_modules directory that contains all your installed packages. Importing from node_modules works seamlessly with tools like Webpack and Babel, which handle the module resolution and transformation process. However, in a setup without these tools, the browser cannot directly understand the CommonJS module format used in node_modules.
Read more regarding creating react app without using create-react-app CLI from my chatgpt discussion:
https://chatgpt.com/share/348e6fa8-e962-4c35-ad80-35dd3d843c01
