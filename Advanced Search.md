# Advanced Search

## 高级搜索

[Advanced Search](https://www.2doapp.com/advanced-search/)

2Do boasts the most powerful search engine on the App Store. Combined with the power of dynamic Smart Lists (a.k.a Saved Searsches) you can create highly specific filters that match your needs.

2Do 可以说拥有 App Store 同类 app 中最强大的搜索引擎。结合动态智能列表，（即 收藏的搜索）你可以根据你的需求创建非常具体的过滤器。

### Searching for Actions, Task Types, & Task Attributes

### 搜索动作，任务类型和任务属性

You can use any of the following reserved search keywords (without quotes) to filter on specific tasks. This is extremely useful when combined with dynamic Smart Search Lists. You could, for example, create a smart list on the term ‘type:audio’ and quickly navigate to all tasks with Audio notes without hunting through a long list (and without the need of changing sort options).

你可以使用下列任一搜索关键词（不带引号）来筛选出具体的任务。这一功能搭配动态智能列表格外有用。比如，你可以根据关键词 “type:audio” （类型：音频）来创建一个智能列表，它可以让你快速找出所有备注中包含音频的任务，而不用在一个长长的列表中搜寻（也不需要改变排序选项）。

- “type: action” – will return all tasks with any action set
- “type: action” - 找出所有带有任意动作的任务
- “type: call” – will return all tasks with a Call action
- “type: call” – 找出所有带有 电话 动作的任务
- “type: sms” – will return all tasks with a SMS action
- “type: sms” – 找出所有带有 短信 动作的任务
- “type: email” – will return all tasks with an Email action
- “type: email” – 找出所有带有 电邮 动作的任务
- “type: browse” – will return all tasks with a URL action
- “type: browse” – 找出所有动作域中带有 URL 的任务 
- “type: visit” – will return all tasks with a Visit action
- “type: visit” – 找出所有带有 到访 动作的任务
- “type: google” – will return all tasks with a Google Search action
- “type: google” – 找出所有带有 谷歌搜索 动作的任务


- “type: audio” – will return all tasks with an Audio file
- “type: audio” – 找出所有带有音频附件的任务
- “type: pict” – will return all tasks with a Picture attachment
- “type: pict” – 找出所有带有图像附件的任务
- “type: note” – will return all tasks with notes
- “type: note” – 找出所有带有备注的任务


- “type: proj” – will return all projects
- “type: proj” – 找出所有（类型是）项目（的任务）
- “type: chck” – will return all checklists
- “type: chck” – 找出所有（类型是）清单（的任务）
- “type: task” – will return all tasks (not checklists or projects)
- “type: task” – 找出所有（类型不是项目或清单）的任务


- “type: hiprio” – will return all high-priority tasks
- “type: hiprio” – 找出所有优先级为高的任务
- “type: medprio” – will return all medium-priority tasks
- “type: medprio” - 找出所有优先级为中的任务
- “type: lowprio” – will return all low-priority tasks


- “type: lowprio” - 找出所有优先级为低的任务
- “type: repeat” – will return all recurring tasks
- “type: repeat” - 找出所有重复性的任务
- “type: overdue” – will return all overdue tasks
- “type: overdue” - 找出所有过期的任务
- “type: tomorrow” – will return all tasks due tomorrow
- “type: tomorrow” - 找出所有明天到期的任务
- “type: today” – will return all tasks due today
- “type: today” – 找出所有今天到期的任务
- “type: donetoday” will return all tasks that were completed today
- “type: donetoday” 找出所有今天完成的任务

### Searching for Tags

### 搜索标签

To look for tasks with the tags ‘home’ and ‘work’, you can type the following in the search field:

用以下的语法来搜索同时带有 ‘home’ （家中）和 ‘work’ （工作）两个标签的任务：

```
tags: home, work
```

To filter on all tasks that have at least one tag set, type the following:

以下的语法可以筛选出所有 “至少带有一个标签” 的任务：

```
tags: ?
```

Or to filter on all tasks without tags, you would type:

以下语法则可以筛选出所有不带任何标签的任务：

tags: ~

### Soundex

### 模糊音匹配

The Soundex Search capability of 2Do is perhaps the most understated, probably because no other application offers anything like it.

2Do 的模糊音匹配搜索可能是最被忽视的能力，或许是因为没有其他任何应用有类似的能力吧。

When taking notes, synchronizing tasks from an external source, or adding quick ToDos, one doesn’t always remember how one spelled a particular name, a place or the not-so-obvious spelling mistakes one made. That should be the least of one’s worries.

当添加备注，从外部源同步任务，或者是快速添加任务时，我们可能并不总能记起某个名字地点的具体拼写，也可能犯一些不那么明显的拼写错误。这些是我们最不应该操心的。

Thankfully with Soundex (which is ON by default and can be switched OFF) you don’t need to worry about all this when searching through your tasks. Soundex matches on similar sounding words (thus the name), which is what you want when looking through ToDos and their associated Notes, Tags etc.

模糊音匹配（默认打开，可以选择关闭）正是为了这个目的存在的。有了这个功能，你在搜索任务的时候就不需要关心上面提出的问题了，只需照你所想在待办事项及其关联的备注中查找，它会自动匹配读音接近的单词（这也是 Soundex 这个名字的由来）。