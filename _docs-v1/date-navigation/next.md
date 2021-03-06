---
title: next
type: method
since_version: 1.3
---

Moves the calendar one step forward (either by a month, week, or day).

<div class='spec' markdown='1'>
.fullCalendar( 'next' )
</div>

If the calendar is in `month` view, will move the calendar forward one month.

If the calendar is in `basicWeek` or `agendaWeek`, will move the calendar forward one week.

If the calendar is in `basicDay` or `agendaDay`, will move the calendar forward one day.

Example using `next` with an external button:

```js
$('#my-next-button').click(function() {
  $('#calendar').fullCalendar('next');
});
```

<div class='version-info' markdown='1'>
In versions 1.0 through 1.2.1, this option was known as *prevMonth*.
</div>
