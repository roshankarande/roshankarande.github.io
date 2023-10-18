+++
author = "Roshan Karande"
title = "Julia Packages"
date = "2022-02-05"
description = "Create beautiful videos"
featured = true
tags = [
    "julia"
]
series = [
    "julia"
]
draft = true
+++

Some random text


{{% notice note "Note" %}} This is a standard "note" style.{{% /notice %}}

{{% notice info "Info" %}} Here is the "info" style. {{% /notice %}}

{{% notice tip "Tip" %}} Here is a "tip" variant of a notice. {{% /notice %}}

{{% notice warning "Warning" %}} Here is the "warning" flavor of a notice. {{% /notice %}}

{{% notice tip "Complex Notices are Possible!" %}}
This is a notice that has a lot of various kinds of content in it.  

* Here is a bulleted list
* With more than one bullet 
    * And even more than one level

Code blocks are fine here, too....
```csharp
public void SayHello()
{
    Console.WriteLine("Hello, world!");
}
```
{{% /notice %}}


{{% notice tip "Productivity Booster!" %}}
If you're using VS Code for your editing, copy the `.vscode\clarity.code-snippets` file into a `.vscode` root folder on your repo.  This will enable you to type
`note` then `<tab>` then choose with up/down arrows which flavor notice you want, then `<tab>` again to provide a title, then `<tab>` to add your content!

![](/images/Note-Snippet.gif)

To use the snippet, you need to first **enable quickSuggestions for Markdown** (one time only):

1. Go to `Preferences->Settings` then search for `quickSuggestions`
1. Follow the link to Edit in settings.json
1. Toward the bottom of the file, paste in the following JSON:
```
"[markdown]":  {
    "editor.quickSuggestions": true
  }
```
4. Close and save the settings.
{{% /notice %}}