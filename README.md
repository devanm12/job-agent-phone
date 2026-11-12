# Job Agent: phone app

The phone side of Job Agent (a personal job-search tool). One static page, installed to the home screen.
It holds no keys and no data: on first launch it asks for a Supabase project URL and publishable key, then a login,
and keeps them on the phone. All data access is checked by Supabase against that login.
