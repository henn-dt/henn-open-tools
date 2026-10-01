# Screenshots for the guide

The images [`../help.md`](../help.md) expects, by file name. Drop a PNG in here under the exact
name and it appears; nothing else has to be edited.

Named for what they show rather than numbered, because the guide's steps get reordered and
numbered names go stale the moment they do.

| File | What it shows |
|---|---|
| `mcpstart-works.png` | Rhino's command line right after `MCPStart` succeeds |
| `plugin-manager.png` | Tools → Options → Plug-ins, with RhinoOuiRelay in the list |
| `toolbar.png` | The four toolbar buttons, cropped tight |
| `settings-window.png` | The settings window as it opens, nothing filled in |
| `mcpconnect-copy.png` | The `MCPConnect` window, copy button circled |
| `router-dot-green.png` | The router row with a green dot |
| `router-dot-red.png` | The router row with a red dot, hovered so the tooltip shows |
| `start-link-warning.png` | The warning shown before connecting, all text readable |
| `settings-connected.png` | Settings with the link running |
| `openwebui-api-key.png` | Open WebUI → Settings → Account → API keys |
| `settings-openwebui.png` | The Open WebUI box in settings, filled in |
| `local-network-prompt.png` | The browser's own local-network permission prompt |
| `openwebui-enable-tool.png` | The chat's tools menu, Rhino switched on |
| `chat-first-reply.png` | A chat describing the open model |
| `monitor-window.png` | The monitor window |

## Taking them

- **PNG**, captured at 100% display scaling. A screenshot taken on a 150% display and shrunk
  looks soft.
- **Crop to the subject.** A full-screen shot of a 4K monitor renders as an unreadable strip.
- **Blur every key**: the bridge API key, the Open WebUI API key, anything key-shaped in the log.
  Blur it in the image — a black box someone can crop is not redaction, and neither is a key
  that was only selected rather than covered.
- **One Rhino theme throughout**, light or dark. Mixing them makes the guide look broken.
- Keep each file under about 300 KB. They are committed to the repository and every reader
  downloads them.
- Use an example Open WebUI address you are happy to publish, and a model you do not mind
  showing.
