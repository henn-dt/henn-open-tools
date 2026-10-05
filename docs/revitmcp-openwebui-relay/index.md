# Using Revit with Open WebUI

<!-- TODO: one paragraph on what the plugin does, with 2-3 example prompts. -->

It is an independent, experimental tool developed in-house at HENN.
It is not made by Autodesk and not by Open WebUI.

---

## Contents

- [Read this part first](#read-this-first)
- [What you need before you start](#requirements)
- [Setting it up — once](#setup)
  - [Step 1 — Open the settings](#step-1-settings)
  - [Step 2 — Connect](#step-2-connect)
  - [Step 3 — Fill in your Open WebUI details](#step-3-open-webui-details)
  - [Step 4 — Tell Open WebUI about it](#step-4-integration)
  - [Step 5 — Reload your browser](#step-5-reload)
  - [Step 6 — Try it](#step-6-try-it)
- [Using it day to day](#day-to-day)
- [When something goes wrong](#troubleshooting)
  - [Nothing happens when I click connect](#connect-error)
  - [Connected, but the chat can't see any Revit tools](#no-tools)
  - [It worked yesterday and today it doesn't](#stopped-working)
  - [I need to report a problem](#report-a-problem)
- [Things worth knowing](#worth-knowing)
- [Words you'll see](#glossary)

---

## Read this part first {#read-this-first}

<!-- TODO: confirm what the chat model can do in Revit (run code? edit/delete elements? touch files?)
     and whether there is any confirmation step, then state it plainly. -->

When you connect, **the chat model can ...**

In practice, that means:

- **Save your work before you connect.** Try it on a copy of a model first, not on something you
  care about. <!-- TODO: central/workshared models? -->
- **Only connect to an Open WebUI you trust.**
- **Watch what it does.**

If any of that is not acceptable for the machine you are on, stop here.

---

## What you need before you start {#requirements}

<!-- TODO: confirm each of these. -->

1. **Windows, and Revit <versions>.**
2. **<The Revit-side MCP server / dependency>**, working in Revit.
3. **An Open WebUI you can log into**, in a browser on this same computer.
4. **Open WebUI permissions to create API key and add user-specific integrations.**
5. **The plugin, installed from its `.yak` package / installer.** <!-- TODO: how it is installed, and where the buttons appear (ribbon tab?) -->

![Revit with the plugin loaded](images/plugin-loaded.png)
<!-- capture: the Revit ribbon tab/buttons added by the plugin -->


---

## Setting it up — once {#setup}

You only do this once. After that, connecting is one click.

### Step 1 — Open the settings {#step-1-settings}

<!-- TODO -->

![The settings window as it opens](images/settings-window.png)
<!-- capture: the whole settings window, nothing filled in yet -->


### Step 2 — Connect {#step-2-connect}

<!-- TODO: what to click, any warning shown, what "connected" looks like. -->

![The warning shown before connecting](images/start-link-warning.png)
<!-- capture: the whole dialog, with all of its text readable -->

![Settings once the link is running](images/settings-connected.png)
<!-- capture: blur any key -->


### Step 3 — Fill in your Open WebUI details {#step-3-open-webui-details}

- **Base URL** — <!-- TODO -->
- **User API key** — <!-- TODO; link to the Open WebUI API key docs as in the Rhino guide -->

![The Open WebUI box in settings, filled in](images/settings-openwebui.png)
<!-- capture: blur the key field -->


### Step 4 — Tell Open WebUI about it {#step-4-integration}

<!-- TODO -->

### Step 5 — Reload your browser {#step-5-reload}

<!-- TODO: same as the Rhino guide if the flow is identical (reload, new chat, local network prompt). -->

![The browser asking to allow access to devices on the local network](images/local-network-prompt.png)
<!-- capture: the browser's own permission prompt, not an Open WebUI dialog -->


### Step 6 — Try it {#step-6-try-it}

In the new chat, activate the tool

![Turning the Revit tool on in an Open WebUI chat](images/openwebui-enable-tool.png)
<!-- capture: the tools menu in the chat box, with the Revit entry switched on -->

and then type:

> <!-- TODO: a harmless first prompt, e.g. "Describe the active Revit project. Do not change anything." -->

If it answers with something about your model, you're done.

![A chat describing the open Revit model](images/chat-first-reply.png)
<!-- capture: the question and the answer together, on a model you do not mind showing -->


---

## Using it day to day {#day-to-day}

1. Open Revit.
2. <!-- TODO: connect -->
3. Go to Open WebUI, activate the tool, and chat.

<!-- TODO: how to disconnect, and whether closing the window / Revit stops it. -->

---

## When something goes wrong {#troubleshooting}

### Nothing happens when I click connect {#connect-error}

<!-- TODO -->

### Revit says it's connected, but the chat can't see any Revit tools {#no-tools}

<!-- TODO: probably the same likely causes as the Rhino guide: browser not reloaded, different web address, local network access blocked. -->

### It worked yesterday and today it doesn't {#stopped-working}

<!-- TODO -->

### I need to report a problem {#report-a-problem}

<!-- TODO: where the log / monitor is and what to send. -->

![The monitor window, showing status and log](images/monitor-window.png)
<!-- capture: blur anything key-shaped in the log -->


---

## Things worth knowing {#worth-knowing}

<!-- TODO: e.g. multiple open Revit sessions/targets, stopping is not undo, workshared models. -->

---

## Words you'll see {#glossary}

| In the plugin | What it means |
|---|---|
| <!-- TODO --> | |
