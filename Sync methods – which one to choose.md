# Sync methods – which one to choose

同步方式 - 如何选择

[原文地址：Sync methods – which one to choose](https://www.2doapp.com/sync-methods-which-one-to-choose/)

2Do supports synchronization between multiple Macs, iOS and Android devices running a copy of the app. With synchronization set up, your lists and tasks will appear on all devices without extra effort on your part.

2Do 支持多台 Mac，iOS 和安卓设备间的同步。设置好同步以后，你的列表和任务就将会出现在你所有的设备上。

2Do supports a number of popular cloud solutions: iCloud, Dropbox, Toodledo and CalDAV (custom iCal servers). There are, however, a set of caveats with each of these sync methods. The main problem stems from the fact that 2Do supports far more properties for a task than any of these cloud solutions. Things like Tags, Recurring options, Alerts, Embedded sounds and pictures are extra information you can assign to your tasks in 2Do,but these don’t translate well to the supported sync methods. You can find out more about each sync method and its associated caveats in the following paragraphs:

2Do 支持多种流行的云端服务：iCloud，Dropbox，Toodledo 和 CalDAV。（自定义 iCal 服务器）不过，这些同步方式都有各自的不足。这些不足主要是由于对一个任务而言，2Do 所能涵盖的属性条目要远大于这些同步方式所能涵盖的。任务的额外信息，比如标签，重复选项，闹铃，内嵌声音和图像等等，无法被这些同步方式完美支持。下面的段落将会详细解释每种同步方式和他们各自的不足：

### Sync using Dropbox

使用 Dropbox 同步

##### Advantages

优点

- Supported by Mac, iOS and Android
- 支持 Mac，iOS 和 安卓
- All your List Groups, Lists, Smart Lists, Task with their attachments and alarms will sync across all other devices running 2Do
- 所有的列表组，列表，智能列表，任务，附件和闹铃提醒都会在所有运行 2Do 的设备间同步。
- Supports automatic background sync
- 具备后台自动同步能力
- Extremely robust and reliable
- 非常稳定可靠
- Supports automatic recovery after network failures or other similar situations
- 具有在断网或者其他类似情况发生后自动恢复的能力
- **Recommended** sync method of choice
- **推荐采用**的同步方式

##### Caveats

不足

- Unlike iCloud and Toodledo, Dropbox does not have a web-interface for managing tasks. This really isn’t an issue if you only ever use your devices to manage and sync your tasks.
- 不像 iCloud 和 Toodledo，Dropbox 同步方式没有网页版界面可供管理任务。如果你一直都只用设备来管理任务的话，这其实也不是事儿。

**译者注**：据推特上发布的消息，2Do 官方已经在开发自己的网页版界面了。

### Sync using iCloud

使用 iCloud 同步

##### Advantages

优点

- Supported by iOS and Mac OS X
- 支持 iOS 和 Mac OS X
- Your lists and tasks from the Reminders app (on iOS or Mac) will automatically sync with 2Do
- iOS 和 Mac 上的提醒 app 中的列表和任务会自动和 2Do 同步
- You will be able to create tasks using Siri on iOS (iPhone / iPad / iPod)
- 可以使用 Siri 来创建任务。
- You can access your synced tasks online using a browser (www.icloud.com)
- 可以通过访问 [www.icloud.com](www.icloud.com) 来管理任务。
- Syncing is Fast, and 2Do will automatically be able to perform sync in the background or at various intervals
- 同步速度快，同时 2Do 将自动获得后台同步的能力
- Your lists and tasks will sync with any other client connected to your iCloud CalDAV account
- 列表和任务将会和任何其他连接到你的 iCloud CalDAV 账户的客户端保持同步
- Pictures and audio notes from 2Do will sync across to other devices running 2Do
- 2Do 中的图像和声音记录将会同步到其他运行 2Do 的设备上
- Multiple alarms on a single task in 2Do will sync across to Reminders as-is
- 2Do 中单个任务上的多个闹铃将会原样同步到提醒中

##### Caveats

不足

- Smart lists from 2Do will not sync to the Reminders app (on iOS / Mac)
- 智能列表无法同步到提醒 app 中
- Projects and checklists from 2Do will appear as simple tasks in Reminders but will, however, sync as projects and checklists to other devices running 2Do
- 2Do 中的项目和清单将会直接以任务的形式在提醒中出现，不过在其他运行 2Do 的设备上会以项目和清单的形式同步
- Tags from 2Do will not appear in the Reminders app
- 2Do 中的标签不会出现在提醒 app 中
- Only tags assigned to a task in 2Do will sync across to other devices running 2Do. Unused tags will not sync.
- 只有在 2Do 中分配给了某个任务的标签会同步到其他运行 2Do 的设备上；未使用的标签不会同步

### Sync using Toodledo

使用 Toodledo 同步

##### Advantages

优点

- Supported by iOS, Android and Mac
- 支持 iOS，安卓和 Mac
- You can access your synced tasks online using a browser (www.toodledo.com)
- 可以通过访问 [www.toodledo.com](www.toodledo.com) 来管理任务
- If you have a Toodledo Pro / Plus account, your projects and checklists from 2Do will sync as projects and checklists to Toodledo
- 如果你有 Toodledo Pro 或者 Plus 账户，那么 2Do 中的项目和清单会以同样的形式同步到 Toodledo 
- Use email to create tasks and sync with 2Do. Toodledo gives you a unique email-address to which you can email tasks. This allows you to add tasks to Toodledo (and thus to 2Do) from any email client. You can even use Siri to compose these emails for you.
- 通过 email 来创建和同步任务。Toodledo 会给你分配一个用于投递任务的 email 地址，从而让你可以从任意的邮件客户端向 Toodledo 中创建任务并同步到 2Do。你甚至可以让 Siri 来帮你写这些邮件。
- Tags will sync from 2Do to Toodledo
- 2Do 中的标签会同步到 Toodledo
- Repeating tasks will sync to Toodledo
- 重复任务会同步到 Toodledo

##### Caveats

不足

- Automatic background sync is not available as an option. You will have to click on the Sync button each time you wish to sync. This is because Toodledo puts a limit on the number of times a device can sync (along with the number of tasks that it can sync at one time) and will suspend the account if it’s syncing too often. If automatic background sync is important to you, please explore the other sync options such as Dropbox or iCloud.
- 没有自动后台同步的选项，你必须点击同步按钮来手动同步。这是因为 Toodledo 限制了每个设备可同步的次数，（同时也限制了每次可同步的任务数）如果某个账户同步过于频繁，会被停用。如果自动后台同步对你来说很重要的话，请选择其他同步方式，比如 Dropbox 或者 iCloud
- Smart lists from 2Do will not sync to Toodledo
- 2Do 中的智能列表无法同步至 Toodledo
- Projects and checklists from 2Do will appear as simple tasks in Toodledo if you don’t have a Toodledo Pro / Plus account but will, however, sync as projects and checklists to other devices running 2Do
- 如果你没有 Toodledo Pro 或者 Plus 账户的话，2Do 中的项目和清单只会以简单任务的形式同步到 Toodledo，但会在其他运行 2Do 的设备上同步为项目和清单
- Only tags assigned to a task in 2Do will sync across to Toodledo. Unused tags will not sync.
- 只有在 2Do 中分配给了某个任务的标签会同步到 Toodledo 上；未使用的标签不会同步
- Audio and picture attachments in 2Do will not sync to Toodledo or to other devices running 2Do
- 2Do 中的声音和图像附件不会同步到 Toodledo 或其它运行 2Do 的设备上
- Alarms from 2Do will not sync to Toodledo
- 2Do 中的闹铃不会同步到 Toodledo
- Emoji UTF-8 characters cannot be used in task titles or notes as Toodledo does not support them. In fact, ToodleDo will replace Emoji characters with question marks, and all tasks that had an Emoji will be duplicated: one will have the Emoji, the other will not.
- UTF-8 编码的 Emoji 字符不能用于任务标题或备注中，因为 Toodledo 不支持它们。Toodledo 会将所有的 Emoji 字符替换为问号，并且所有包含 Emoji 的任务都会出现一个不包含 Emoji 的复件。