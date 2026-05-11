<h1 align="center">
🖥️ Desktop in the Age of Background Apps: <br>Why DE Needs a Rethink<br>
    <p align="center"> <a href="https://t.me/rawr_time"> <img src="assets/RUS.png" height="25" alt="На русском" /></a> </p>
</h1><br>

## 🔻Introduction

Modern desktop environments in “adult” operating systems (Windows, Linux, macOS) are complex applications that often trace their roots back to systems designed at the dawn of OS development. Explorer, GNOME, KDE, and macOS all originate from an era when the computer user experience was radically different from what it is today.  

This essay looks at the problems of modern desktop environments from a usability perspective and proposes a way to address them, placing the responsibility on desktop-environment makers—because today they are, in many ways, the ones implementing and shaping this kind of functionality.  

In this text we’ll walk through the evolution from programs to applications, unpack the issues created by the rapid rise of mobile software, introduce a new classification of software by usage type, and use it to propose a solution to the problems described above. We’ll also explore how desktop environments could evolve on top of this foundation—so the slogan “a desktop environment for people, not people for the desktop environment” can become real.<br><br><br><br>

## 🔸Chapter 1. How programs turned into applications

This chapter is about the history of applications. First, let’s align on terminology so we don’t get confused later.

**Program** — in the broadest sense, an “instruction for the computer”: do X → output Y.  

**Application** — the same program, but *packaged for humans*: it has a UI, you can install it, open it, close it, and in general it’s clear how to live with it.

Put simply: a program becomes an application when it’s used not only by engineers, but by regular people. An interface appears, along with common scenarios, habits, and interaction rules.

“Programs” include drivers, the operating system kernel, OS components, and things launched by the user. “Applications” are the familiar tools: messengers, browsers, games, and so on.

To see how the way people interact with computers has changed, I’ll break the story into stages. Quick disclaimer: I’m not a historian of software or hardware, so the split is **simplified**. The years in this chapter are a guideline, not a strict mapping to specific events.<br><br>

### Stage 1 — “the reign of programs”「1946 - 1965」

In 1946, **ENIAC**—one of the first programmable computers—was demonstrated. It’s a convenient starting point for an era where the main “control organ” was the program itself (more precisely, sets of instructions for a computer).

Before that, calculating machines could only perform pre‑wired operations. ENIAC at first was even reprogrammed **manually**—by physically rewiring cables and reconfiguring circuits.

Computers quickly grew more complex, and one of the key milestones was the emergence of **first‑generation operating systems**. By today’s standards they were very simple: they mostly ensured **sequential execution** of programs.

If we look for early “proto‑applications,” they’re surprisingly **games**. For example, Alexander Douglas’s Tic‑Tac‑Toe (1952). A modern UI barely existed yet, but interactivity was already appearing.

Finally, high‑level languages. **Fortran** and **BASIC** made programming much easier. Programs began to be distributed via removable media and shared from user to user. For that era, this was a “peak”: programs became more widespread, understandable, and accessible.

**Key milestones:**

- **1946 ▸** one of the first programmable computers — **ENIAC**;
- **1950 ▸** the ENIAC card reader appears;
- **1952 ▸** an early interactive program (a predecessor of applications) — Tic‑Tac‑Toe;
- **1957 ▸** the first popular high‑level language — **Fortran**;
- **1964 ▸** the mass‑adopted language — **BASIC**.

**Summary:** the “reign of programs” era is characterized by an almost complete lack of UI, running “one program at a time,” and the beginning of programs being shared between people.<br><br>

### Stage 2 — the transition to applications「1960 - 1985」

In the second stage, there are **many** programs, and alongside them **applications** begin to take shape. With BASIC, more and more people enter development: some write tools for themselves, others do it for fun. And when there are many programs, the question becomes inevitable: how do you make them usable for someone other than the author?

The obvious step is to **shape an interface**. Typing commands by hand, reading a README, and remembering launch parameters is only tolerable up to a point. UI is an evolutionary answer to rising complexity.

In 1965, **second‑generation operating systems** appear: multitasking, user sessions, and—most important for this story—a **file system**. It changes the rules: programs become files, code is separated from the “hardware” and from a specific medium.

Against this backdrop, **UNIX** (1969) stands out. It becomes one of the most influential operating systems, and crucially it is no longer tied to a specific machine. Previously it was often the case that software was written for a specific computer. UNIX helps cement the idea that the same software can live across different configurations.

Once a program has a broad audience, investing in it becomes worthwhile. Developers more often do what we now consider normal: a convenient UI, clear workflows, and “human packaging.”

On the user‑computing side, important events happen too:

- **XEROX Alto** (1973) — one of the first computers with an advanced graphical interface, influencing the principles of modern OSes.
- **Apple II** (1977) — one of the first truly mass‑market PCs, where “packaged” applications spread widely.

Early mass applications appear: text editors (Apple Writer), spreadsheets (VisiCalc), and so on. Software stops being a toy for engineers: it now solves practical tasks for “regular” users—write, calculate, plan.

**Key milestones:**

- **1965 ▸** second‑generation OSes: multitasking, user sessions, file systems;
- **1969 ▸** **UNIX** — an OS independent from specific hardware, expanding the audience for software;
- **1973 ▸** **XEROX Alto** — an early mature GUI and principles of future OSes;
- **1977 ▸** **Apple II** — a mass‑market PC.

**Summary:** the move from “bare programs” to applications was enabled by OS development and abstraction away from hardware. UI and mass computers turned software into a product: users began to choose what’s “convenient,” and developers began to profit from applications.<br><br>

### Stage 3 — the evolution of apps: desktop and early mobile「1980 - 2006」

The third stage is when applications become the norm rather than the exception.

In 1984, Apple releases the **Macintosh**—one of the first mass‑market computers with a windowed interface “like XEROX,” but actually polished into something usable. In 1985, **Windows 1.0** ships, and later **Windows 3.0** (1990), which quickly becomes a business standard.

What many still remember appears: the “office suite.”  

Word processors (WordPerfect, Word), spreadsheets (Lotus 1‑2‑3, Excel), presentations (PowerPoint). Applications become everyday work tools for millions.

In parallel, a “small screen world” starts to mature. In the 1980s, portable computers (for example, the TRS‑80 Model 100) appear with simple text editors and calendars. In the mid‑1990s, an important shift happens:

- **Palm OS** (1996) and **Windows CE** (1996) bring mass‑market PDAs;
- the idea of syncing with a PC appears — a “companion app.”

Mobile phones begin to get built‑in games and organizers. And with **Java ME** (2000), users can install third‑party apps even on “regular” feature phones.

**Key milestones:**

- **1984 ▸** **Macintosh** — a mass GUI + mouse;
- **1985 ▸** **Windows 1.0** — the start of Microsoft’s graphical OS era;
- **1990 ▸** the rise of office suites (Microsoft Office);
- **1996 ▸** **Palm Pilot** — a mass‑market PDA;
- **2000 ▸** **Java ME** — mobile apps on feature phones.

**Summary:** applications split into two camps — desktop (complex and powerful) and mobile (simple, efficient, designed for small screens).<br><br>

### Stage 4 — the mobile app explosion「2002 - 2014」

The fourth stage is when mobile apps catch up to desktop—and then, in many ways, start to “pull” users toward themselves.

In 2002, **Nokia 7650** on Symbian ships—one of the first mass‑market smartphones, capable of installing programs (via Bluetooth/internet) and featuring a camera.

But the key turning point is the **iPhone (2007)**. At first it had no third‑party apps: Steve Jobs suggested web apps. But in 2008, the **App Store** arrives: 500 apps at launch and 10 million downloads in the first week. After that, there’s no going back—an app becomes something you can find, buy, and install in a couple taps.

Google launches **Android** with its own store (Android Market → Google Play). A “mobile ecosystem war” begins, alongside explosive growth in categories:

social networks, messengers, mobile games built around touch.

Desktop apps don’t disappear, but their role shifts toward professional tools (Photoshop, AutoCAD, Visual Studio) and demanding games.

**Key milestones:**

- **2002 ▸** **Nokia 7650** (Symbian) — a mass‑market smartphone;
- **2007 ▸** **iPhone** — the new era of touch interaction;
- **2008 ▸** the launch of the **App Store** and **Android Market**;
- **2010 ▸** **iPad** — tablets and their apps;
- **2012 ▸** Android Market becomes **Google Play**.

**Summary:** mobile apps become the primary way billions of people “use a computer.” App stores solve distribution and monetization. Desktop retains its role mostly in professional and “heavy” scenarios.<br><br>

### Stage 5 — one app across all devices「2012 - present」

The fifth stage is the blurring of boundaries. Almost everyone has a smartphone, and many have laptops and tablets too—and the expectation is simple: **one app should live everywhere**.

Hence the push for cross‑platform: React Native (2015), Flutter (2017), PWAs. Nobody wants to build 3–4 separate clients; they want one product that feels consistent on phones and computers.

A second shift is the business model:

- before: “buy once”;
- now: subscriptions and freemium (Adobe Creative Cloud, Microsoft 365, etc.).

A third is the cloud. Increasingly, an app is a service: data syncs, documents are edited in the browser, and the “desktop version” may be just a shell (Electron). Google Docs, Figma, Notion—exactly this.

OSes themselves move in this direction:

- Apple enables running iOS apps on Macs with M1 (2020);
- Windows 11 adds Android app support (2021).

**Key milestones:**

- **2015 ▸** **Windows 10** and the idea of universal apps (UWP);
- **2017 ▸** **Flutter** — a powerful cross‑platform framework;
- **2020 ▸** **Apple M1** — iOS apps on Mac;
- **2021 ▸** **Windows 11** — Android apps via the Amazon Appstore;
- **2023 ▸** the mass rollout of **AI features** in applications.

**Summary:** the difference between “desktop vs mobile” becomes increasingly conditional. Users think less about installation and more about access/subscription/sync. We moved from “programs on disks” to “apps as services.”<br><br>

### 🧾Chapter 1 recap

We traveled from “programs as a set of commands” to applications as products and services—with UIs, habits, and an expectation of constant availability across devices. This shift made software mass‑market and convenient, but it also mixed different “cultures” of use (desktop and mobile) in one world. Next, it’s important to see how this collision shows up on the desktop today—and why familiar desktop‑environment mechanisms no longer cope.<br><br><br><br>

## 🔸Chapter 2. The problem

Since the 1980s, the world of software has changed dramatically. You can clearly say: desktop and mobile apps are two different worlds:

- desktop (Photoshop, Visual Studio, Excel) grew out of “many features → many windows → many settings”;
- mobile (Telegram, maps, weather) grew out of “one screen → one task → minimal taps.”

And everything seems fine: you work on a big screen and chat on your phone. But on the desktop, these two worlds are forced to live under the same OS rules—rules that were historically written for the “classic” desktop class of applications.

The problem isn’t that “we couldn’t do better before,” but that the industry didn’t have time to rebuild the desktop OS model around new habits. Now, as more software lives in the background and competes for attention, rebuilding these rules becomes not a whim, but a practical necessity.<br><br>

### The notification system

Take notifications. Windows (and most Linux environments) has a system notification center where apps can send messages.

For “classic” desktop apps, that’s enough: an antivirus or backup utility speaks rarely and to the point.

But messengers and “mobile‑spirited” apps live at a different pace. They need:

- grouping by chats,
- reactions,
- quick reply directly from the notification,
- custom sounds,
- unread badges,
- etc.

What do developers do? They build their own. Telegram shows its own popups over the system ones. Discord has its own. Slack has its own. As a result, three different windows can appear in the same corner of the screen—each with different behavior, styling, and closing logic. No beauty, no consistency.<br><br>

### The tray problem

Next: the system tray (the area near the clock). The tray idea is good: give background apps a small icon so they stay “at hand” without getting in the way. But many Windows users, looking at their tray, will see a huge number of icons hidden behind an arrow.

For example, the GNOME team refused to implement the classic tray in their DE, because it almost inevitably turns into a graveyard of icons and a UX landfill: half the icons live there for unclear reasons and it’s hard to tell what they even do. Their solution is radical: “remove the problem by removing the object” — minimalism at its purest.

With the arrival of “mobile‑spirited” apps, the tray really does easily become a dump:

Telegram, Discord, Steam, Epic Games Launcher, cloud drives, password managers, peripheral utilities—many apps want to add their own icon there.

The tray becomes not a “quick actions panel,” but an indicator of “how much stuff you have running.” Many apps also add themselves to autostart without asking and slow system boot.

A positive tray example is **Telegram** on Windows. By default it opens a full window on the taskbar. But a typical messenger workflow is “launch and forget,” while notifications arrive in the background. Telegram can live in the tray properly: it minimizes, keeps working, and the icon becomes the main entry point.

A bad example is when an app—while minimized—still sits both on the taskbar and in the tray. Why? Because there is no clear OS‑level rule like “a background app doesn’t need taskbar space.” Developers decide every time—and decide differently.<br><br>

### Blurred boundaries between “application” and “service”

Desktop OSes poorly distinguish between:

- an application you actively work in for hours,
- and a lightweight client/agent that should pop up for a second and then fade into the background.

Look at game launchers: Steam, Epic Games, GOG Galaxy. They start with the system, sit in the tray, download updates, send discount notifications. In essence, they’re background services with a storefront. But the system treats them like “normal apps”: they can open windows, take screen space, and stay running after you close them.

The flip side is that some heavy desktop apps (for example, Adobe Creative Cloud) behave like mobile: constantly updating, living in the tray, pushing marketing notifications. This isn’t about technology—it’s about philosophy and the lack of clear system boundaries.<br><br>

### 🧾Chapter 2 recap

The conflict shows up as a set of symptoms: inconsistent rules for background life, fragmented UX solutions, and unclear boundaries of what counts as an “app” versus a “background agent.” As long as the system doesn’t distinguish behavior types, each product will improvise. So the next step is to give ourselves a language and a model: what classes of software exist, and what rights/expectations should each have?<br><br><br><br>

## 🔸Chapter 3. A new software classification

Based on the problems above, I’ll introduce a classification that helps us understand the needs and behavior of different types of software.

Outside the scope are apps for wearables (watches/glasses). Here we consider software for smartphones, tablets, and PCs.<br><br>

### System services

This is the system layer: components and background processes that keep the OS, hardware, and other applications running.

Usually they have no UI, or the UI exists only for configuration. They are not meant for “constant interaction.”

System‑level software includes:

- OS components (kernel, subsystems) — manage memory, processes, drivers, and system calls;
- device drivers — the layer between the OS and hardware;
- system services/daemons — background processes (sshd, cron, print spooler, etc.);
- OS/software update agents;
- antivirus engines (often a service + a separate management utility).

Key criteria:

- **activity:** background‑only (a settings utility may exist);
- **lifecycle:** start with the system and live as long as the OS is on;
- **notifications:** not sent directly; interaction via logs/events;
- **autostart/services:** yes—this is their nature.

In short, it’s infrastructure. Not desktop, not mobile—foundational.<br><br>

### Primary applications

These are applications whose core function almost always requires an **open window**.

Examples: IDEs, editors, Notion/Anytype, Photoshop, Audacity, and so on. Computer games belong here too.

They **don’t need the tray**. They consume a lot of resources and are rarely used as background companions alongside other heavy software.

Key criteria:

- **activity:** main window (taskbar as the access point);
- **lifecycle:** close the window = the app exits (no “minimize to tray”);
- **notifications:** allowed, but rare and meaningful;
- **autostart/services:** forbidden by default (if needed at all—only via explicit user action).

The point is simple: these are heavy tools and they should not turn into background parasites.<br><br>

### Auxiliary applications

These are the ones that **naturally live in the background**: VPN, email, messengers, torrent clients, music, etc.

Their typical loop is “open → minimize → open → minimize.” They need the tray as their primary presence: icon, status, quick actions. These are direct descendants of the mobile philosophy.

Key criteria:

- **activity:** background; often lives in the tray; can open a window and then be minimized;
- **lifecycle:** staying alive after closing the window is allowed;
- **notifications:** allowed; advanced scenarios may exist;
- **autostart/services:** allowed, but only with explicit user consent and transparent control.<br><br>

### Secondary applications

This is a “middle” class: interactive, episodic apps that you open “when needed” and close without wanting them to remain in the background.

Examples: browser, calculator, file manager, image viewer, timer, etc.

Key criteria:

- **activity:** typically an active window, sometimes short‑lived background work;
- **lifecycle:** episodic use; close the window = exit;
- **notifications:** optional and usually limited;
- **autostart/services:** forbidden by default (if present at all—it’s an exception).

Important principle: if the user **explicitly closes** a secondary application, it should not linger in the background as a “tail.”<br><br>

### 🧾Chapter 3 recap

The classification turns the vague “apps behave weirdly” into concrete classes with different lifecycles: what must live only as a window, what may stay in the background, and what should be a service without UI at all. This sets the rules of the game and lets us discuss constraints without taste wars. Next comes the main question: how do we make these rules work not by “agreement,” but technically—at the OS level and through its APIs?<br><br><br><br>

## 🔸Chapter 4. How the operating system should change

From the previous chapters, two things are clear:

1) modern desktop OSes do not distinguish app classes—messengers and Photoshop live by the same rules;

2) we proposed a classification: system services, primary, auxiliary, and secondary applications.

Now the main question: what exactly needs to change so this works in practice, not just on paper?<br><br>

### Explicitly declaring an app class

When publishing an app (or in a manifest), the developer must specify a class: **primary / auxiliary / secondary**.

If no class is specified, the OS treats the app as **primary by default** (with strict limits on background behavior and the tray).

The user must be able to override the class at any time (for example, move a torrent client from “primary” to “auxiliary”).

To ensure this isn’t just a declaration, “background capabilities” should be exposed as dedicated system APIs:

- showing a tray icon,
- adding to autostart,
- sending notifications (including advanced features).

The app gets access only through these APIs, and the OS decides to allow or deny based on the class (and user settings).

For legacy apps without a manifest, the OS should prompt on first launch to choose a class: a short dialog with 2–3 options and examples. Skipped it? Choose later.

To reduce abuse (spam/malware), access to tray/autostart/advanced notifications should come with safeguards:

- clear labeling of notification sources,
- preventing imitation of system dialogs,
- a quick “reset permissions” path by downgrading the class in settings.

OS settings should add new sections:

- **Background agents** — a list of all auxiliary apps: autostart, background activity, tray use, resource usage;
- **Autostart** — a centralized list with toggles and warnings;
- **App class** — overriding the class for each installed program.

Apps without a declaration get “primary” status with strict rules: autostart only if the user adds it; minimizing to tray is forbidden; notifications are basic. The OS may maintain a database of popular apps and their recommended class until apps adopt these features.

**Class behavior at the OS level:**

**Primary apps:**

- autostart forbidden (except explicit user action);
- minimizing to tray forbidden;
- notifications only through the system center (limited);
- presence on screen via the taskbar.

**Auxiliary apps:**

- a legal place in the tray — a persistent icon;
- autostart allowed, but only with a mandatory prompt on first launch;
- notifications with advanced capabilities;
- background allowed; services are possible, but fully controllable by the user (clear names, visibility, ability to disable). The user should see that “TelegramUpdateService” is indeed a Telegram service.<br><br>

**Secondary apps:**

Similar to primary, but with nuances:

- no permanent tray icon, but may show a temporary background‑task indicator (and disappear when not needed);
- may expose extended quick actions via the taskbar context menu.<br><br>

### Reworking the tray and the taskbar

The tray should become an **information hub** for apps that genuinely need to live in the background. It keeps the “home” for auxiliary applications, lets users pin them and open them, but doesn’t stop there.

This is, in essence, the answer to the argument that made GNOME try to “bury” the classic tray: yes—if everyone is allowed to do anything, it will get cluttered. But instead of cutting the whole thing, we can introduce OS‑level rules and limitations: who has the right to be in the tray, how, when, and why.

As in Windows today, right‑clicking an icon should provide a quick‑actions menu so the user can change app state without opening a window.

The taskbar, meanwhile, is the territory of primary and secondary apps. Secondary apps can get richer actions via the context menu (as Windows Explorer does).<br><br>

### Fixing the notification system

The goal is to make it no longer beneficial for apps to “build their own” on top of the system center.

The OS should provide several access tiers:

- **Basic (for all apps):**
    - text;
    - icon;
    - buttons;
    - progress bar;
- **Advanced (for auxiliary apps):**
    - an input field for quick reply;
    - interactivity;
    - grouping;
    - notification categories.

The OS also needs a proper **Do Not Disturb** mode and **notification sounds**: apps should not play their own sound—an app sends an event, and the OS plays the sound chosen by the user (the app may provide a default).<br><br>

### 🧾Chapter 4 recap

We now have the “skeleton” of a solution: app classes become not an abstraction, but the basis for rights and constraints (tray, notifications, autostart, background) via unified system APIs. This returns control to users and predictability to developers: fewer hacks, more proper system scenarios. Next, we can talk about the “layers on top”: what new UX mechanisms become possible once the platform has this kind of framework.<br><br><br><br>

## 🔸Chapter 5. How the OS could evolve after the foundation

The changes above help us organize applications inside the OS. In this chapter we’ll look at what functionality could be built on top of that foundation so the OS feels even more predictable and comfortable for everyday computer work.<br><br>

### Notification categories

OS‑level categories let you separate notifications by type and importance and give the user real control.

Example: if Steam adopts this, a user could configure separately:

sales, friend messages, gifts—and assign each its own sound/priority.

For Telegram, it would make sense to split notifications by account for people who use multiple accounts.

Users should be able to:

- disable promotional notifications entirely while keeping messages;
- assign a separate sound;
- allow a category even during Do Not Disturb.

As with mobile OSes, the system cannot “force” developers to use categories, but we can expect conscientious developers to adopt them.<br><br>

### System widgets and extending the tray

Once the tray is “cleaned up,” it becomes clear that it can be more than a place for icons.

Mobile OSes have long developed widgets, Dynamic Island, and “live” notifications. On desktop, an analogue could be fast, visual control over background apps: timers, music, downloads, voice channels.

If auxiliary apps often go to the background (Discord, Telegram), tray widgets help you understand what’s happening without switching back to the window: who’s speaking in a voice channel, what track is playing, how many percent have downloaded.

**Notification badges** on a tray icon should also be extended so they can show not only “unread count,” but small statuses/icons (from a set or custom) to indicate modes: “silent,” “VPN connected to X,” and so on.<br><br>

### System modes

Another powerful layer is **system modes**. Yes, they require manual setup and not everyone uses them. But for those who do, they offer real value.

A mode can define:

- which apps are active/frozen,
- which notifications are allowed through,
- how the desktop/pins look,
- which sounds and rules apply.

Imagine a typical workday. You turn on “Work” mode and the OS reshapes app behavior:

- Discord stays in the background as an auxiliary app: tray shows voice status, notifications only for @mentions.
- Telegram doesn’t spam: messages are quiet, “promo” and reactions have their own category.
- Steam in “Work” doesn’t show sales, and in “Rest” may remind you about a sale.
- VPN lives as a compact tray button/widget, and autostart is transparently visible in settings.

The point isn’t that “features appeared.” The point is that the OS finally manages this centrally—and the user controls the background, not the other way around.<br><br>

### 🧾Chapter 5 recap

When the system has a framework and control, “tasty” add‑ons become possible—not as app‑specific hacks, but as a unified platform: notification categories, tray widgets/info panels, and work modes. These ideas don’t replace the foundation—they unlock its potential. UX stops being a collection of compromises and becomes a manageable environment. Next we just need to lock in the overall conclusion and state what exactly matters to change in our approach to DE/OS.<br><br><br><br>

## 🔺Conclusion

In short, the problem with modern desktop environments isn’t that “everything is implemented badly,” but that the world of applications changed faster than the rules of the desktop environment did. The desktop inherited habits from the “windows and programs” era, and then collided with the philosophy of “app‑services” that live in the background and constantly demand attention. When the system doesn’t distinguish these behavior types, chaos begins: each product pulls the blanket toward itself and invents its own workarounds.

This essay takes that thought to a practical conclusion: to restore order, we need to stop treating symptoms and give the OS/DE a clear framework—a classification of applications and technically enforced rules for access to background capabilities.

Once the system has control and unified rules, it also gains room to evolve—smarter notifications, a more meaningful tray, system modes, and workflows that help rather than hinder. And that’s the moment when the desktop environment stops being a set of compromises and becomes what it should be: a tool built for people.<br><br><br><br>

## ⚠️ A note to developers

If you share these thoughts and want to try bringing them to life—let’s do it together.

Help this text reach more people: share the essay, translate it into other languages, discuss the theses, argue with them, propose alternatives. Build prototypes, draft APIs, sketch interfaces, and experiment—even small contributions add up and move the industry.

A desktop environment should adapt to people, not teach people to live by the rules of an accidentally‑evolved UX.<br><br><br><br>
