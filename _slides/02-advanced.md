---
layout: slides
title: Advanced Concepts
permalink: /slides/advanced/
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

# Bonsai
### Advanced Concepts

---

### Sharing observable sequences

![Branching](../../assets/images/branching-simple.svg)
<!-- .element: style="display: inline-block; vertical-align: top;" -->
![Subjects (Publish)](../../assets/images/subjects-publish-simple.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: top; padding-left: 120px;" -->

--

### Sharing observable sequences

![Publish](../../assets/images/publish.svg)
<!-- .element: style="display: inline-block; vertical-align: top;" -->
![Replay](../../assets/images/replay.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: top; padding-left: 40px;" -->

--

### Sharing observable sequences

![Subjects (Publish)](../../assets/images/subjects-publish.svg)
<!-- .element: style="display: inline-block; vertical-align: top; padding-left: 120px;" -->
![Subjects (Replay)](../../assets/images/subjects-replay.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: top; padding-left: 120px;" -->

---

### Higher-Order Operators

![Concatenate video files using first order operators](../../assets/images/concatfile-firstorder.svg)

--

###### Enumerate Files

![Enumerate all file names in a folder](../../assets/images/concatfile-enumeratefiles.svg)

--

###### Window Workflow

![Create sequences of frames from file names](../../assets/images/concatfile-window.svg)

--

###### Concat

![Combine all sequences of frames into a single sequence](../../assets/images/concatfile-combine.svg)

---

###### Buffer

![Buffer](../../assets/images/buffer.svg)

---

###### TriggeredBuffer

![TriggeredBuffer](../../assets/images/triggeredbuffer.svg)

---

###### Window

![Window](../../assets/images/window.svg)

---

###### TriggeredWindow

![TriggeredWindow](../../assets/images/triggeredwindow.svg)

---

<!-- .element: data-transition="default none" -->
###### Transform

![Transform](../../assets/images/transform.svg)

--

<!-- .element: data-transition="none default" -->
###### Select

![Select](../../assets/images/select.svg)

---

###### SelectMany

![SelectMany](../../assets/images/selectmany.svg)

</script>
</section>