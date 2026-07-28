# Date and Time Tools

Date and time tools support timestamps, conversions, schedules, and calendar-style workflows.
They are useful for logging, automation, planning, and debugging time-based systems.

---

## Purpose

The date and time family covers conversion, comparison, formatting, timezone handling, and scheduling helpers.
These tools must be predictable and easy to read.

---

## Included Tools

### Unix Timestamp Converter
Converts between Unix timestamps and human-readable date values.

### ISO 8601 Converter
Converts to and from ISO 8601 date strings.

### Timezone Converter
Converts a date and time across timezones.

### Date Diff Calculator
Shows the difference between two dates in clear units.

### Age Calculator
Calculates age from a date of birth.

### Leap Year Checker
Shows whether a given year is a leap year.

### Week Number Calculator
Displays the week number for a given date.

### Relative Time Helper
Shows the relative distance between dates and times.

### Cron Parser
Parses cron expressions into readable schedule details.

### Cron Generator
Builds cron expressions from selected schedule settings.

### Working Days Calculator
Calculates working-day counts between dates.

### Calendar Range Helper
Helps define date ranges for dashboards and planning flows.

---

## Interaction Standards

Date and time tools must support:

- Clear input labels
- Timezone-aware output where relevant
- Copyable results
- Human-readable formatting
- Mobile-safe controls
- Deterministic conversion behaviour

---

## Output Standards

Outputs must clearly show the source timezone, target timezone, date format, and conversion logic when relevant.

---

## Common Use Cases

- Scheduling work
- Automation planning
- Logs and timestamps
- Calendar calculations
- Analytics debugging
- Timezone debugging

---

## Quality Rules

Date and time tools must not hide timezone assumptions.
If a conversion depends on locale, offset, or formatting mode, that must be obvious.

---

## Future Expansion

This family may later include:

- Business days planner
- Recurring schedule builder
- Time range visualiser
- Date arithmetic helper
- Natural language time parser
