# Project Style Guide

## Table of Contents
1. [General Guidelines](#general-guidelines)
2. [Nuxt.js](#nuxtjs)
3. [Laravel](#laravel)
4. [Commit Messages](#commit-messages)
5. [Code Reviews](#code-reviews)

## General Guidelines
- Write meaningful comments and keep them up to date.
- Follow naming conventions consistently.
- Ensure your code is clean and readable.

## Nuxt.js
### Project Structure
- Follow the default Nuxt.js project structure.
- Organize components, pages, and store modules logically.
- Place reusable components in the `components/` directory.
- Use `layouts/` for application layouts.

### Components
- Name components with PascalCase.
- Use single-file components (`.vue`).
- Keep template, script, and style tags organized in single-file components.

### Templates
- Use `v-bind` and `v-on` shorthand (`:` and `@`).
- Avoid inline styles; use scoped CSS instead.
- Prefer computed properties over methods in templates for reactive data.

### Scripts
- Use ES6+ syntax.
- Organize `data`, `computed`, `methods`, `watch`, and lifecycle hooks logically.
- Use Vuex for state management.

### Styling
- Use `scoped` CSS to avoid conflicts.
- Follow a consistent naming convention for CSS classes (e.g., BEM or utility-first).

## Laravel
### Project Structure
- Follow the default Laravel project structure.
- Use `app/` for application logic, `routes/` for route definitions, and `resources/` for views.

### Controllers
- Keep controllers concise; delegate complex logic to service classes.
- Name controllers with a singular resource name (e.g., `UserController`).

### Models
- Follow Laravel's naming conventions for models (singular, PascalCase).
- Use Eloquent relationships and accessors/mutators effectively.

### Migrations
- Use descriptive names for migrations.
- Group related changes into a single migration where appropriate.

### Routes
- Use route model binding where possible.
- Group routes logically and use route prefixes and namespacing.

### Blade Templates
- Use Blade's templating features effectively.
- Organize templates into `layouts`, `partials`, and `components`.

## Code Reviews
- Review code for readability, performance, and security.
- Provide constructive feedback.
- Ensure tests pass before approving a pull request.
- Use pull requests for all changes to the master branch.

