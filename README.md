# rails-react - Ruby on Rails + React w/ TypeScript via Webpacker

This project is a new Ruby on Rails project that adds support for React + TypeScript via [Webpacker](https://github.com/rails/webpacker).

This code accompanies the blog entry at: <https://firxworx.com/blog/coding/configuring-ruby-on-rails-to-support-react-typescript-with-webpacker/>

Refer to `app/javascript/components` to find the `App.tsx` component. 

The React entry point is `app/javascript/packs/hello_react.tsx` which is included via `javascript_pack_tag` in the `<head>..</head>` of the `app/views/layouts/application.html.erb` template.

To start the rails development server on <http://localhost:3000>, run:

```sh
rails s
```

For documentation on the webpack dev server and other webpack capabilities refer to: <https://github.com/rails/webpacker#development>.
