# HTML Forms

## What is a Form?

A Form is used to collect data from users and send it to a server.

Examples:

- Login Form
- Registration Form
- Search Bar
- Contact Form

Common websites like Google, YouTube, Amazon, and Flipkart use forms.

## Form Tag

The `form` tag is used to create a form.

```html
<form>
</form>
```

## Action Attribute

The `action` attribute specifies where the form data should be sent.

```html
<form action="/search">
</form>
```

Example:

```html
<form action="https://www.youtube.com/results">
</form>
```

When the form is submitted, the data is sent to the specified URL.

## Input Element

The `input` element is used to receive data from users.

```html
<input type="text">
```

## Name Attribute

The `name` attribute identifies the input field.

```html
<input type="text" name="search_query">
```

The form uses the name attribute while sending data.

Example:

```text
/results?search_query=html
```

Here:

- `search_query` → name attribute
- `html` → user input

## Common Input Types

| Type | Purpose |
|--------|---------|
| text | Text input |
| email | Email input with validation |
| password | Hides entered text |
| number | Numeric input |
| tel | Phone number input |
| date | Date picker |
| time | Time picker |
| color | Color picker |
| file | File upload |
| checkbox | Select options |

Example:

```html
<input type="email">
<input type="password">
<input type="checkbox">
```

## Button Types

| Type | Purpose |
|--------|---------|
| submit | Submits the form |
| button | Normal button |
| reset | Resets all form fields |

Example:

```html
<button type="submit">Login</button>
<button type="reset">Reset</button>
```

## Placeholder Attribute

Provides a hint inside the input field.

```html
<input type="email" placeholder="Enter your email">
```

## Required Attribute

Makes a field mandatory.

```html
<input type="email" required>
```

The form cannot be submitted until the field is filled.

## Minlength and Maxlength

Used to limit the number of characters.

```html
<input type="password" minlength="8" maxlength="20">
```

## Label Tag

The `label` tag describes an input field.

```html
<label for="email">Email</label>
<input type="email" id="email">
```

The `for` attribute should match the input's `id`.

### Benefits

- Better accessibility
- Easier to use forms
- Helps screen readers

## Simple Login Form

```html
<form action="/login">

  <label for="email">Email</label>
  <input
    type="email"
    id="email"
    name="email"
    required
  >

  <br><br>

  <label for="password">Password</label>
  <input
    type="password"
    id="password"
    name="password"
    minlength="8"
    required
  >

  <br><br>

  <button type="submit">Login</button>

</form>
```

## Summary

- Forms are used to collect user data.
- The `form` tag creates a form.
- The `action` attribute specifies where data is sent.
- The `input` element receives user input.
- The `name` attribute identifies form data.
- Different input types are available for different use cases.
- Labels improve accessibility.
- Validation can be added using attributes like `required`, `minlength`, and `maxlength`.
