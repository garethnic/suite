Using alerts(), prompts(), confirms() breaks the workflow of users. Based on historical software practices most users who come across these modals will simply dismiss them without being concerned about the consequences. These modals can also become annoying if used incorrectly.

This rule will also be triggered when a page opens a prompt by default without the user doing anything.

# How do I fix this ?

Design your website to be clear and concise. Use simple mechanisms to notify users. Rethink the process flow of your website.

There are alternative approaches one can take to avoid using these modals, for example:

* Highlight fields in forms that have validation errors.
* Use CSS and Javascript to create clear notifications for users.
* Use simple `<input>` for user input.

# Resources

* [JavaScript's prompt, confirm and alert considered “old-fashioned”](http://programmers.stackexchange.com/questions/106031/javascripts-prompt-confirm-and-alert-considered-old-fashioned/106039)
* [Should alert boxes be avoided at any cost?](http://ux.stackexchange.com/questions/4518/should-alert-boxes-be-avoided-at-any-cost)
