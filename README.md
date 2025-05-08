# Kamili ERP Notebook 🧠

A collection of reusable Laravel/PHP code snippets and patterns I’ve discovered or created during development — helpful across various modules and projects.

---

## 🗂️ Table of Contents

- [🔐 Authentication Helpers](#authentication-helpers)
- [📦 Service Layer Snippets](#service-layer-snippets)
- [📄 Form Request Validation](#form-request-validation)
- [🧩 Blade Components](#blade-components)
- [🔁 Reusable Eloquent Queries](#reusable-eloquent-queries)
- [⚙️ Route & Middleware Patterns](#route--middleware-patterns)
- [🧪 Test Utilities](#test-utilities)

---

## 🔐 Authentication Helpers

```php
// Check if current user is admin
if (auth()->check() && auth()->user()->hasRole('admin')) {
    // logic...
}
