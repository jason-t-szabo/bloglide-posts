# Welcome to your blog

This folder is your desk drawer. Notes you start here are saved and backed up,
but nobody can see them. When a post is ready, you move it out of `_drafts` and
it goes live.

That's the whole system. Write here, move to publish.

---

## Publishing a post

1. Write your note. New notes start in `_drafts` automatically.
2. When it's ready, drag it out of `_drafts` and drop it in the main folder.
3. Press your publish shortcut (or tap the publish button on your phone).

Within a minute or two it's on your blog.

**To unpublish**, move the file back into `_drafts` and publish again. Move it
back out later and it returns to the same web address as before — as long as you
don't rename it. Renaming a published post changes its web address, and any link
someone saved will stop working.

---

## What to put at the top of a post

Nothing, if you don't want to. A post with no settings at all works fine — your
blog will use the filename as the title.

When you do want more control, Obsidian's **Properties** panel (the box at the
top of a note) is where these go.

| Property | What it does |
| --- | --- |
| `title` | The headline. Without it, the filename is used. |
| `description` | A one-line summary shown under the title on your home page. |
| `heroImage` | A picture at the top of the post. See below. |
| `heroImageAlt` | A short description of that picture for people who can't see it. |
| `topics` | Subject labels. See below. |
| `visibility` | Leave this alone for now — see [Coming later](#coming-later). |

There are also `pubDate` and `updatedDate`. You don't need to touch these — your
blog fills them in the first time a post publishes and whenever you change it.
If you'd rather set a date yourself, type one and it will be used instead.

**Spelling matters.** If you type `heroImge` instead of `heroImage`, publishing
stops and you get an email. That's deliberate — a typo in `visibility` could
otherwise put a post online that you meant to keep private, so your blog refuses
to guess.

---

## Pictures

Paste or attach a picture the normal way and it lands in your `images` folder
automatically. Nothing else to do.

**Please add a description to every picture.** For an attached image, type it
between the square brackets: `![A red bicycle against a brick wall](...)`. For a
hero image, fill in `heroImageAlt`. This is what people using screen readers
hear instead of the picture, and search engines use it too.

If a picture is missing or its name is misspelled, the post still publishes —
the picture is just left out, and you get a warning by email. Watch the
capitalisation: `Photo.JPG` and `photo.jpg` are different names as far as your
blog is concerned.

---

## Topics

Topics are the subject labels readers see. Each one gets its own page listing
every post about it.

Add them in the Properties panel under `topics`, one per line. They can contain
spaces, capitals, and punctuation — `Web Development`, `Node.js`, and
`día a día` all work.

**Topics are not the same as Obsidian's tags.** Obsidian's `tags` property is
yours to use however you like — `#needs-photos`, `#half-finished`, whatever helps
you organise. None of it is ever shown to readers. Only `topics` is public.

Don't worry about typing a topic exactly the same way every time. `Web
Development`, `web development`, and `WEB DEVELOPMENT` are all treated as the
same topic, and the spelling you use most often is the one readers see.

---

## Your About page

Create a note called `About` in the main folder (not in `_drafts`) and it
becomes the About page on your blog. Write whatever you like in it. Until you
do, visitors see a short placeholder.

---

## Writing on your phone

Everything works the same. Two differences worth knowing.

**Your phone saves and publishes on a timer** — roughly every ten minutes after
you stop typing. That's why notes start in `_drafts`: your work is backed up
constantly without anything going public by accident.

**Open the app before you start writing, and give it a moment.** It pulls down
changes when it opens. If you write on your phone without doing that, and you
also changed something on your computer, the two copies disagree and your phone
gets stuck.

A good habit: open the app, wait a beat, then write. Publish when you're done.

---

## When something goes wrong

**A post didn't appear.** Check your email — GitHub sends a message when
publishing fails. It will name the file and the problem. Most often it's a
misspelled property name.

**Your phone says it can't update, or shows an error about conflicts.** This is
the one problem that's easier to start over than to fix. First make sure
anything you wrote on your phone has been published. Then delete the vault from
your phone and set it up again from scratch. Nothing is lost — everything lives
on the server. It takes about five minutes.

Don't spend an hour trying the repair commands. They often don't work, and the
error messages aren't much help.

**Your phone stopped connecting, months after it was working.** Your access
token has expired — they last a year. Create a new one on GitHub and paste it
into the Git plugin's settings where it asks for a password.

---

## A few don'ts

- **Don't use `[[double brackets]]` for links.** They show up as literal
  brackets on your blog. Obsidian is set up to write ordinary links for you.
- **Don't rename a published post** unless you're willing to break links people
  have saved.
- **Don't give two posts names that differ only in capitals or punctuation.**
  `Tag Test` and `tag-test` both want the same web address, and publishing will
  stop until you rename one.
- **Don't post-date a post.** It won't wait until then to publish — it'll go up
  immediately with a date in the future, which confuses feed readers.
- **Don't change Obsidian's settings on your phone and your computer in the same
  session** without publishing in between.

---

## Coming later

Two features are planned but not built yet:

- **Private posts** — visible only to you
- **Friends posts** — visible to people you've approved

The `visibility` property already exists for these, but until they're ready,
setting it to anything other than `public` simply keeps the post off your blog
entirely. It won't be lost — it stays in your folder and will appear once the
feature arrives.

---

*Keep this file here. It's what makes the `_drafts` folder exist on a new
device, and deleting it would stop new notes from landing in the right place.*
