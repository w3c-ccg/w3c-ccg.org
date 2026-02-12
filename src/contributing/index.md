---
layout: base.njk
basedir: ../..
title: Contributing to our specifications
description: A guide to using GitHub Codespaces to contribute to our specifications.
---

<div class="hero">
  <div class="container">
    <h1>Contributing to our specifications</h1>
  </div>
</div>

<div class="content-section">
  <div class="container">

# Using GitHub Codespaces to Contribute to our Specifications

[GitHub Codespaces](https://github.com/features/codespaces) provides a
cloud-hosted development environment that allows you to edit and preview HTML
files directly in your browser.

You can use the following guide to get started:

1. Login to <https://github.com/>
2. Visit a repository with a specification in it (such as <https://github.com/w3c/vc-render-method>)
3. Click the green "Code" button in the top-right area of the repo
4. Click "Create codespace on main" -- this will load VS Code in the browser (so it avoids the installation, etc.)

  </div>
</div>

<div class="content-section">
  <div class="container">

VS Code should now be opened in your browser. Next, we need to install a preview extension.

<strong>NOTE:</strong> Some repositories may already have a "devcontainer" setup that includes the
necessary extensions. If you see a pop-up asking you to "Trust & Install" an
extension, you can skip the next few steps and just click that button.

1. Click the "Extensions" icon - 5th icon in the left sidebar (looks like 4 squares with the top-right one rotated).
2. Search for "live server" in the search box that appears in the "Extensions: Marketplace" list.
3. Click "install" on the "Live Server" extension from "Ritwick Dey".
4. Click "Trust & Install" on the pop-up.

  </div>
</div>

<div class="content-section">
  <div class="container">

Next, let's preview the existing HTML...

1. Click on the "Explorer" icon - 1st icon on the left sidebar (looks like 2 documents stacked)
2. then, click index.html in the file list.
3. In the bottom-right you should see the words "Go Live". Click that.
4. A new tab should open showing the rendered HTML from index.html

  </div>
</div>

<div class="content-section">
  <div class="container">

Now, let's make some changes...
1. Switch back to the tab with the editor in it.
2. In the `<title>` on line 4, change any of that text or add something to it.
3. The editor will auto-save (but don't worry! it's not publishing anything...yet).
4. Switch to the tab with the preview in it. You should see the change in the main title/header of the document.

  </div>
</div>

<div class="content-section">
  <div class="container">

Lastly, let's setup a branch so you can contribute those changes...
1. Go back to the editor tab.
2. In the search box at the top type `>` create branch (including the `>` character) and pick "Create branch..."
3. Type a branch name like changing-section-whatever (no spaces, but otherwise it can be whatever you want) and press enter.
4. In the bottom left corner confirm that you see the new branch name (it's very tiny text...)
5. You should see a blue circle with the number 1 in it on the "Sources" icon (3rd icon in the left sidebar). Click that.
6. A list should appear showing index.html in the list of Changes.
7. If you were/are ready to send in your changes, type a message in the "Message" box and click the green "Commit" button.
8. Once you are done making and committing changes, you can click the little "Create Pull Request" icon above the message box (second icon in that group of 3; has a + on it).
9. That will load another panel where you can give your Pull Request a title and description and click "Create"
10. Once you've created a Pull Request, the group will review it. If changes are needed, you can reopen the Codespace and continue editing.

  </div>
</div>

<div class="content-section">
  <div class="container">

When you are done editing (or experimenting), you can close the tab. However,
the codespace will continue to run, so to clean-up, you can visit
https://github.com/codespaces/ where you should see the codespace(s) in an
"Owned by ..." list at the bottom of that page. There is an ellipsis icon to the
right of each codespace. Click that and then choose "Stop codespace" (if you're
done for now, but plan to return to it) or "Delete" if you're completely done
and have sent in your Pull Request.

GitHub should auto-delete any codespaces that do not have any pending changes in
them (i.e. you sent in a pull request already).
  </div>
</div>