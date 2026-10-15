AN Dashboard gives employees a clear view of their working time in Kimai. The main balance, today's recorded time, monthly and yearly differences, vacation days, and sick days are shown as easy-to-read cards. A balance chart and detailed values are available on a separate page.

## Features

- Personal work-time balance for today, the current month, the current year, and the total calculation period
- Live updates while a timesheet entry is running
- Vacation and sickness figures with clear day labels
- Weekly, monthly, and yearly balance trends
- Team and employee reports for users with the required permissions
- CSV and PDF exports
- German and English interface

## Requirements

- Kimai 2.20 or newer
- PHP 8.2, 8.3, or 8.4

## Installation

Place the plugin in `var/plugins/ANDashboardBundle` and clear the Kimai cache:

```bash
bin/console cache:clear --env=prod
```

The **Work-time balance** link appears directly below **Dashboard** in the main navigation. Employees need the `view_own_timesheet` permission to open their personal overview. Team and employee filters are available to users with `view_other_timesheet`.

## Availability

Contact PCSG using the button on this page to request the current plugin package and terms.

## Support

For installation help or bug reports, contact [support@pcsg.de](mailto:support@pcsg.de).
