# Earth Day Awareness Event

Professional Earth Day Awareness Event invitation for environmental advocates and educational institutions.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Education, Environmental Conservation
- **Message Type:** Events
- **Tags:** sustainability, earthday, awarenessevent

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/earth-day-awareness-event.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/earth-day-awareness-event/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.earth-day-awareness-event',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
