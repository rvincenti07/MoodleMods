**Open / Closed Date — Bulk Quiz Date Management**

This Moodle local plugin lets teachers update the opening and closing dates for multiple quiz activities at once. From a course’s Bulk actions toolbar, select quizzes from the same section, choose an opening date, a closing date, or both, and apply the changes.

Each date has its own Enable checkbox. Disabling a date removes that restriction from the selected quizzes. If both dates are enabled, the plugin checks that the opening date comes before the closing date. After a successful update, Moodle returns to the section and displays a confirmation.

The plugin changes only quiz opening and closing dates. It does not change assignment dates, quiz due dates, or individual student and group overrides. Users need the `moodle/course:manageactivities` capability in the course.

**Installation note:** The current version requires a small Moodle core change to add the action to the course Bulk actions toolbar.
