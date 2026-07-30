# Neurix

### An offline note-taking application for Windows 10 and 11.

Neurix stores your notes locally on your computer. It doesn't require an internet connection, cloud account, or external database. Notes are stored as Markdown files and can be edited or previewed directly within the application.

<p align="center">
  <img src="Assets/dashboardapp.png" width="850">
</p>

## Why I made it

I wanted a note-taking application that was lightweight, fast, and fully local. Most note-taking apps either depended on cloud services, felt too heavy, or included features I didn't need. Neurix is my attempt at building something simple that focuses on writing and keeping notes organized while remaining completely offline.

## Current Features

- Write and edit Markdown notes
- Live Markdown preview
- Local Markdown file storage
- Light, dark, and custom themes
- Pin important notes
- Search notes
- Drag and drop images into notes
- Interactive checklists
- Notes encrypted using Windows DPAPI
- Runs completely offline
  
## Supported Syntax

- Headings (`#`, `##`, `###`)
- Bold and italic text (`*italic*`, `**bold**`, `***bold italic***`)
- Underline (`__underline__`)
- Hyperlinks (URLs)
- Links to notes or categories (`/<note-or-category>/`)
- Interactive checklists
  - `/checkbox` + Enter
  - `/checkbox.true`
  - `/checkbox.false`

## Some Custom Themes I Like

<table>
  <tr>
    <th>Preview</th>
    <th>Accent Color</th>
    <th>Background</th>
    <th>Heading</th>
    <th>Text</th>
    <th>Borders</th>
  </tr>

  <tr align="center">
    <td>
      <img src="Assets/dashboardapp.png" width="220">
    </td>
    <td>
      <div style="width:60px;height:60px;background:#8A5CF6;margin:auto;border:1px solid #444;"></div>
      <code>Blue</code>
    </td>
    <td>
      <div style="width:60px;height:60px;background:#101018;margin:auto;border:1px solid #444;"></div>
      <code>#101018</code>
    </td>
    <td>
      <div style="width:60px;height:60px;background:#576CFD;margin:auto;border:1px solid #444;"></div>
      <code>#576CFD</code>
    </td>
    <td>
      <div style="width:60px;height:60px;background:#CDD6F4;margin:auto;border:1px solid #444;"></div>
      <code>#CDD6F4</code>
    </td>
    <td>
      <div style="width:60px;height:60px;background:#252525;margin:auto;border:1px solid #444;"></div>
      <code>#252525</code>
    </td>
  </tr>
</table>

## Built With

- C#
- .NET 10
- WPF (Windows Presentation Foundation)

## Contributing

Neurix is still under development. Suggestions, bug reports, and pull requests are welcome.

> Note: This README reflects the current state of the project and will be updated as new features are added.
