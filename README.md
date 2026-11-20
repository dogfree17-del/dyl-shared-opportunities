# Dell Young Leaders – shared opportunities

A log of every opportunity already sent out in the weekly Dell Young Leaders career mailer.

The `jobmailer` skill reads `shared_opportunities.csv` before each mailer and leaves out
any job or teaching post that was shared before. It counts as the same opportunity when it has the same link,
or the same company, title and location. After each mailer, the skill adds the new opportunities to the log.

| Column | Meaning |
|---|---|
| date_shared | Date of the mailer (YYYY-MM-DD) |
| type | `job` or `teaching` (Edupstairs teaching posts) |
| company | Employer or school |
| opportunity | Job title, or subjects and grades for teaching posts |
| location | Town or city |
| link | Application link |
| faculties | Faculty emails (or teaching phase) it was sent in |

Only public job advert information is stored here, no student data.
