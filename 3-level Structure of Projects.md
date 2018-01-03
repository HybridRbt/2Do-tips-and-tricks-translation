# 3-level Structure of Projects

项目的三层结构

![img](https://www.2doapp.com/files/2013/11/Project-featured.jpg)

You may encounter a situation where a project is just too big to only consist of sub-tasks. Instead, it may be appropriate to break it down further into sub-projects, each comprising of their own sub-tasks – a hierarchy of projects and sub-projects if you like. 2Do, for valid reasons, does not provide support for sub-projects as such a feature would in fact add needless complexity to the overall structure of your tasks, not to mention dropping synchronization support for well-known calendaring protocols such as CalDAV, which 2Do supports via iCloud Sync for now.

有时你可能会遇到项目过于复杂的情况，无法简单地用子任务来分化。更好的办法是将其分解为子项目，在每个子项目中再分解出各自的子任务，以此建立一个项目和子项目的分层结构。然而，2Do 却不支持这种分层功能，但这是有原因的。支持这种功能会给你的任务总体结构带来不必要的复杂性，更重要的是，这会造成 2Do 无法兼容通用的日历同步协议，比如通过 iCloud Sync 实现同步的 CalDAV。

2Do has an elegant solution for this use-case, though. Simply create a new List as your main project, and then add projects to form sub-projects within. Your sub-tasks would then serve as the main tasks at the lowest level. To go one step further, you could create a List Group to serve as your parent project / areas of responsibility, with Lists forming sub-projects within.

不过对于这种使用场景，2Do 提供了另外的解决方案。你只需要创建一个列表作为你的主项目，然后添加项目作为子项目，在这之下的最底层则是子项目的子任务。更进一步，你可以创建列表组作为父项目/责任区，然后用列表作为子项目。

This support of using Lists as Projects wasn’t accidental – this was a deliberate attempt in trying to solve the visual aspect of separating areas of concern, without adding support for a limitless task & subtask relationship. Just as you mark a project as ‘complete’, 2Do supports the ability to ‘archive’ lists (equivalent to completing a project and hiding it from view). Simply right-click a list &gt Archive. All archived lists can be found in *Preferences > Protection > Archived*.

这种使用列表作为项目的方法并不是巧合，而是有意为之的，以在“不需要添加可无限拆分的任务-子任务功能”的限制下达到分离关注区的目的。就像你可以标记一个项目为“完成”一样，2Do 也支持“归档”列表（相当于完成了一个项目并将它从视图中隐藏）。只需右键单击一个列表并选择 归档。被归档的所有列表可以在 偏好设置 > 保护 > 归档 中找到。

There are of course known drawbacks to this approach (i.e. of using lists as Projects) – you can’t set dates and priorities to lists. That is unfortunately a small price we pay for clarity and support for keeping synchronization options open to protocols such as CalDAV (which means 2Do can be used with other Calendar / Task managers on other platforms of choice).

当然，用列表当做项目也不是完美的解决方案。比如你不能给列表设定日期和优先级。我们必须做出这些牺牲以换取对像 CalDAV 这样的同步协议的支持。（这样 2Do 才可以和其他的日程和任务管理软件共通）