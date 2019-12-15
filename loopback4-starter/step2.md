A model serves both as a data transfer object (DTO) for representing incoming to-do items (or instances) on requests, as well as our data structure for use with loopback-datasource-juggler.

The purpose of a to-do list is to track tasks. So, your application needs to let you label and differentiate between unique tasks, add extra information to describe those tasks, and finally, provide a way of tracking whether or not they’re complete.

The to-do model has the following properties:

- `id`: a unique id
- `title`: a title
- `desc`: a description that details the specific task to be accomplished
- `isComplete`: a boolean flag for whether or not we’ve completed the task
