
## 🎯 Sprint hiện tại

Deadline: 2026-05-25

```dataviewjs
const tasks = dv.pages('"01 Projects/APF/tasks"').file.tasks;

const total = tasks.length;
const done = tasks.where(t => t.completed).length;
const doing = tasks.where(t => !t.completed && t.text.includes("#doing")).length;
const blocked = tasks.where(t => !t.completed && t.text.includes("#blocked")).length;

dv.paragraph(`**Done:** ${done}/${total}`);
dv.paragraph(`**Doing:** ${doing}`);
dv.paragraph(`**Blocked:** ${blocked}`);
```

