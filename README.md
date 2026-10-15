# Cliffhangers
Devlog for Cliffhangers website


## Tuesday 13/10/2026

Website
- Configured local development environment
- Changed Fonts

Exec Team Page
- Updated executive team information
- Added some new exec team photos - formatted photos to fit
- Altered the formatting for the Night Runners so that they adjusted better for mobile
- Updated headings and descriptions on exec team page

Nav Bar
- Added home, store, about, events and my profile to nav bar
- Made about, events and my profile drop downs to include exec team, club docs, trips, calendar, logbook, membership, gear hire and admin for admin users
- Formatted the nav bar to be narrower
- Added CSS for the nav bar buttons
- Centred the Search bar

To Do
- Fix formatting of burger menu for moblie
- Reformat home page for logged in users
- Check if fonts have become unstable throughout rest of website
- Determine nav locations for incident reports, reimbursements, bug reports (footer)
- Determine nav location for gear hire
- Remove QUT CLIFFHANGERS text from nav bar?
- Make Footer narrower

## Wednesday 14/10/2026

- Fixed formatting of burger menu
- Made Footer narrower
- Added incident report and bug report to footer

## Thursday 15/10/2026

- Added seconder kit request to trip sign up
- Was unable to test due to trip creation error:
"insert into `trips` (`camping_trip`, `catering`, `crag`, `date_from`, `date_to`, `description`, `name`, `signup_close`) values ('0', '0', 'Niderry', '2026-10-17', NULL, NULL, 'Matthew Edwards', '2026-10-15T01:01') - ER_BAD_FIELD_ERROR: Unknown column 'catering' in 'field list'"
- Have commented out catering entry: lines 90-94 in editor.pug - need to check actual database to see how its handled
- Seconder kit drop down appeared as desired
- Need to add field to database, currently doing so breaks as all current trip signups end up missing a field 
