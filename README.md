# README

This project uses the following Ruby gems for frontend styling, task scheduling, JavaScript management, and database handling.

🛠 Ruby Version and Rails version

ruby 3.1.0 (ruby "3.1.0")
Rails 7.0.2 ( "rails", "~> 7.0.2")
Core framework for the application.
Includes ActiveRecord, ActionCable, ActionMailer, ActiveJob, and more.


🚀 Frontend & UI

📦 CSSBundling-Rails (gem "cssbundling-rails")
Provides CSS preprocessor support for Rails.
Supports Tailwind CSS, Bootstrap, PostCSS, and Dart Sass.

📦 Country Select (gem 'country_select', '~> 6.0')
Adds a dropdown select list of countries to Rails forms.
Uses the ISO 3166 standard for country codes.


🔐 Authentication & Security

📦 Devise (gem "devise")
Flexible authentication framework for Rails applications.
Handles sign-in, sign-up, password resets, and account confirmation.


🛠 JavaScript & Hotwire

📦 Importmap-Rails (gem 'importmap-rails')
Enables ESM (ECMAScript Module) imports without Webpack or Node.js.
Loads JavaScript dependencies using import maps in Rails.


📦 Turbo-Rails (gem 'turbo-rails')
Enhances page speed with Turbo Frames & Turbo Streams.
Enables SPA-like navigation without a full-page reload.


📦 Stimulus-Rails (gem 'stimulus-rails')
Adds StimulusJS framework for lightweight, event-driven JavaScript in Rails.
Works alongside Turbo for dynamic UI updates.


📋 Utilities & Task Scheduling

📦 Acts_as_list (gem 'acts_as_list')
Adds sortable lists (e.g., drag-and-drop ordering) to ActiveRecord models.
Useful for task management, menu ordering, and ranking systems.


🛠 Background Jobs & Task Scheduling

📦 Sidekiq (gem 'sidekiq', '~> 5.2.8')
Efficient background job processing using Redis.
Supports asynchronous job execution, retries, and monitoring.

📦 Redis-Client (gem 'redis-client')
Modern Redis client for Ruby with better performance and connection handling.
Works seamlessly with Sidekiq, caching, and pub/sub messaging


📄 PDF Generation & Formatting
📦 Wicked PDF (gem 'wicked_pdf')
Generates PDFs from HTML templates in Rails.
Works with wkhtmltopdf for rendering.


🛠 Utilities & Performance

📦 Coderay (gem 'coderay')
Provides syntax highlighting for code snippets in Ruby applications.
Supports multiple languages like Ruby, Python, JavaScript, etc.