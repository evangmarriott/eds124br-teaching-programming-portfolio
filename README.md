# Evan Marriott · EDS 124BR Portfolio

A course-long collection of programming projects, explanations, teaching ideas, and reflections for EDS 124BR.

**Published site:** https://evangmarriott.github.io/eds124br-teaching-programming-portfolio/

## Add new course work

The site is a static portfolio. Add files in this repository, then add a short card for the work to `index.html` so it appears in the public gallery.

1. Choose **Add file → Upload files** on the [repository page](https://github.com/evangmarriott/eds124br-teaching-programming-portfolio). Upload a video, image, or other supporting file. Keep assets reasonably small and use links for large files or projects hosted elsewhere.
2. Open `index.html` and choose **Edit this file**.
3. In the **Course work** section, copy the existing `<article class="project">…</article>` block and paste it after the previous project. Update the title, type, description, and tags. Link to a Snap project or shared document when relevant.
4. For a video stored in this repository, use a player like this inside the card:

```html
<details class="video">
  <summary>Watch the explanation</summary>
  <video controls preload="metadata" playsinline>
    <source src="your-video.mp4" type="video/mp4">
  </video>
</details>
```

5. Commit the changes to `main`. GitHub Pages publishes the update automatically after its build completes.

A useful entry includes the assignment or project title, what it is for, what you made or learned, and links to the work itself. Keep personal or private course information out of the public repository.
